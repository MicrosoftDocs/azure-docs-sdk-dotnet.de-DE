<Type Name="PoolOperations" FullName="Microsoft.Azure.Batch.PoolOperations">
  <TypeSignature Language="C#" Value="public class PoolOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type PoolOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="43af0-101">Führt die Pool-bezogenen Vorgänge auf Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="43af0-101">Performs pool-related operations on an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ChangeOSVersion">
      <MemberSignature Language="C#" Value="public void ChangeOSVersion (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ChangeOSVersion(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersion(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ChangeOSVersion (poolId As String, targetOSVersion As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersion : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ChangeOSVersion (poolId, targetOSVersion, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-102">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-102">The id of the pool.</span></span></param>
        <param name="targetOSVersion"><span data-ttu-id="43af0-103">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-103">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-104">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-104">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-105">Ändert die Betriebssystemversion des angegebenen Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-105">Changes the operating system version of the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-106">Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="43af0-106">During the change OS version operation, the Batch service traverses the nodes of the pool, changing the OS version of compute nodes.</span></span>  <span data-ttu-id="43af0-107">Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-107">When a compute node is chosen, any tasks running on that node are removed from the node and requeued to be rerun later (or on a different compute node).</span></span>  <span data-ttu-id="43af0-108">Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="43af0-108">The node will be unavailable until the version change is complete.</span></span></para>
          <para><span data-ttu-id="43af0-109">Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben.</span><span class="sxs-lookup"><span data-stu-id="43af0-109">The operation will result in temporarily reduced pool capacity as nodes are taken out of service to have their OS version changed.</span></span> <span data-ttu-id="43af0-110">Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</span><span class="sxs-lookup"><span data-stu-id="43af0-110">Although the Batch service tries to avoid changing all compute nodes at the same time, it does not guarantee to do this (particularly on small pools); therefore, the operation may result in the pool being temporarily unavailable to run tasks.</span></span></para>
          <para><span data-ttu-id="43af0-111">Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-111">When you request an OS version change, the pool state changes to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span></span>  <span data-ttu-id="43af0-112">Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-112">When all compute nodes have finished changing version, the pool state returns to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span></span></para>
          <para><span data-ttu-id="43af0-113">Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern.</span><span class="sxs-lookup"><span data-stu-id="43af0-113">While the version change is in progress, the pool's <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> reflects the OS version that nodes are changing from, and <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> reflects the OS version that nodes are changing to.</span></span> <span data-ttu-id="43af0-114">Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-114">Once the change is complete, CurrentOSVersion is updated to reflect the OS version now running on all nodes.</span></span></para>
          <para><span data-ttu-id="43af0-115">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-115">This is a blocking operation.</span></span> <span data-ttu-id="43af0-116">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-116">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeOSVersionAsync (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ChangeOSVersionAsync(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersionAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ChangeOSVersionAsync (poolId, targetOSVersion, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-117">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-117">The id of the pool.</span></span></param>
        <param name="targetOSVersion"><span data-ttu-id="43af0-118">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-118">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-119">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-119">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-120">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-120">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-121">Ändert die Betriebssystemversion des angegebenen Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-121">Changes the operating system version of the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-122">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-122">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-123">Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="43af0-123">During the change OS version operation, the Batch service traverses the nodes of the pool, changing the OS version of compute nodes.</span></span>  <span data-ttu-id="43af0-124">Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-124">When a compute node is chosen, any tasks running on that node are removed from the node and requeued to be rerun later (or on a different compute node).</span></span>  <span data-ttu-id="43af0-125">Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="43af0-125">The node will be unavailable until the version change is complete.</span></span></para>
          <para><span data-ttu-id="43af0-126">Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben.</span><span class="sxs-lookup"><span data-stu-id="43af0-126">The operation will result in temporarily reduced pool capacity as nodes are taken out of service to have their OS version changed.</span></span> <span data-ttu-id="43af0-127">Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</span><span class="sxs-lookup"><span data-stu-id="43af0-127">Although the Batch service tries to avoid changing all compute nodes at the same time, it does not guarantee to do this (particularly on small pools); therefore, the operation may result in the pool being temporarily unavailable to run tasks.</span></span></para>
          <para><span data-ttu-id="43af0-128">Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-128">When you request an OS version change, the pool state changes to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span></span>  <span data-ttu-id="43af0-129">Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-129">When all compute nodes have finished changing version, the pool state returns to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span></span></para>
          <para><span data-ttu-id="43af0-130">Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern.</span><span class="sxs-lookup"><span data-stu-id="43af0-130">While the version change is in progress, the pool's <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> reflects the OS version that nodes are changing from, and <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> reflects the OS version that nodes are changing to.</span></span> <span data-ttu-id="43af0-131">Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-131">Once the change is complete, CurrentOSVersion is updated to reflect the OS version now running on all nodes.</span></span></para>
          <para><span data-ttu-id="43af0-132">Vorgang zum Ändern des Version wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-132">The change version operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateComputeNodeUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser (string poolId, string computeNodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser(string poolId, string computeNodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreateComputeNodeUser(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateComputeNodeUser (poolId As String, computeNodeId As String) As ComputeNodeUser" />
      <MemberSignature Language="F#" Value="member this.CreateComputeNodeUser : string * string -&gt; Microsoft.Azure.Batch.ComputeNodeUser" Usage="poolOperations.CreateComputeNodeUser (poolId, computeNodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-133">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-133">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-134">Die Id des Serverknotens, in denen das Benutzerkonto, das erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-134">The id of the compute node where the user account will be created.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-135">Erstellt eine <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> , eine neue Compute Knoten Benutzerkonto an, die noch nicht im Batch-Dienst vorhanden ist darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-135">Creates a <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> representing a new compute node user account that does not yet exist in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-136">Ein ungebundenes <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> , ein neues Benutzerkonto, das nicht mit dem Computeknoten hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-136">An unbound <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> representing a new user account that has not been added to the compute node.</span></span></returns>
        <remarks><span data-ttu-id="43af0-137">Um den neuen Benutzer hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-137">To add the new user, call <see cref="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePool () As CloudPool" />
      <MemberSignature Language="F#" Value="member this.CreatePool : unit -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="43af0-138">Erstellt eine Instanz des CloudPool, die entfernt wird und keine Beziehung Konsistenz keinem Pool in der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="43af0-138">Creates an instance of CloudPool that is unbound and does not have a consistency relationship to any pool in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-139">Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> , einen neuen Pool, der nicht mit dem Batch-Dienst hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-139">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> representing a new pool that has not been added to the Batch service.</span></span>
            <span data-ttu-id="43af0-140">Um den Pool der Batch-Konto hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-140">To add the pool to the Batch account, call <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.CloudServiceConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.CloudServiceConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, cloudServiceConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.CloudServiceConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-141">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-141">The id of the pool.</span></span></param>
        <param name="virtualMachineSize">
            <span data-ttu-id="43af0-142">Die Größe der virtuellen Maschinen in den Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-142">The size of virtual machines in the pool.</span></span>  <span data-ttu-id="43af0-143">Finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ für Größen.</span><span class="sxs-lookup"><span data-stu-id="43af0-143">See https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ for sizes.</span></span> <span data-ttu-id="43af0-144">Batch unterstützt alle Azure-Cloud-Dienst-VM-Größen außer sind ExtraSmall, A1V2 und A2V2.</span><span class="sxs-lookup"><span data-stu-id="43af0-144">Batch supports all Azure cloud service VM sizes except ExtraSmall, A1V2 and A2V2.</span></span></param>
        <param name="cloudServiceConfiguration"><span data-ttu-id="43af0-145">Die <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> für den Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-145">The <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> for the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="43af0-146">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-146">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-147">Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="43af0-147">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="43af0-148">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-148">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-149">Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="43af0-149">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43af0-150">Erstellt eine Instanz des CloudPool, die entfernt wird und keine Beziehung Konsistenz keinem Pool in der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="43af0-150">Creates an instance of CloudPool that is unbound and does not have a consistency relationship to any pool in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-151">Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> , einen neuen Pool, der nicht mit dem Batch-Dienst hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-151">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> representing a new pool that has not been added to the Batch service.</span></span>
            <span data-ttu-id="43af0-152">Um den Pool der Batch-Konto hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-152">To add the pool to the Batch account, call <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-153">Informationen zum Azure-gastbetriebssystemfamilien finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/</span><span class="sxs-lookup"><span data-stu-id="43af0-153">For information about Azure Guest OS families, see https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.VirtualMachineConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.VirtualMachineConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, virtualMachineConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.VirtualMachineConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-154">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-154">The id of the pool.</span></span></param>
        <param name="virtualMachineSize"><span data-ttu-id="43af0-155">Die Größe der virtuellen Maschinen in den Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-155">The size of virtual machines in the pool.</span></span> <span data-ttu-id="43af0-156">Https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ für Windows-Größen und https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ für Linux-Größen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="43af0-156">See https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ for windows sizes and https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ for linux sizes.</span></span>
            </param>
        <param name="virtualMachineConfiguration"><span data-ttu-id="43af0-157">Die <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> für den Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-157">The <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> for the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="43af0-158">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-158">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-159">Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="43af0-159">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="43af0-160">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-160">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-161">Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="43af0-161">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43af0-162">Erstellt eine Instanz des CloudPool, die entfernt wird und keine Beziehung Konsistenz keinem Pool in der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="43af0-162">Creates an instance of CloudPool that is unbound and does not have a consistency relationship to any pool in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-163">Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> , einen neuen Pool, der nicht mit dem Batch-Dienst hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-163">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> representing a new pool that has not been added to the Batch service.</span></span>
            <span data-ttu-id="43af0-164">Um den Pool der Batch-Konto hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-164">To add the pool to the Batch account, call <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43af0-165">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.PoolOperations" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-165">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.PoolOperations" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="43af0-166">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="43af0-166">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="43af0-167">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="43af0-167">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="43af0-168">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="43af0-168">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUser">
      <MemberSignature Language="C#" Value="public void DeleteComputeNodeUser (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteComputeNodeUser(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUser(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteComputeNodeUser (poolId As String, computeNodeId As String, userName As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUser : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteComputeNodeUser (poolId, computeNodeId, userName, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-169">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-169">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-170">Die Id der Compute-Knoten, von dem Sie das Benutzerkonto löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="43af0-170">The id of the compute node from which you want to delete the user account.</span></span></param>
        <param name="userName"><span data-ttu-id="43af0-171">Der Name des Benutzerkontos ein, das gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-171">The name of the user account to be deleted.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-172">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-172">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-173">Löscht das angegebene Benutzerkonto aus dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-173">Deletes the specified user account from the specified compute node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-174">Sie können die Löschen eines Benutzerkontos nur, wenn diese wird von einem Serverknoten die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-174">You can delete a user account from a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="43af0-175">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-175">This is a blocking operation.</span></span> <span data-ttu-id="43af0-176">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-176">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteComputeNodeUserAsync (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteComputeNodeUserAsync(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUserAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteComputeNodeUserAsync (poolId, computeNodeId, userName, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-177">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-177">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-178">Die Id der Compute-Knoten, von dem Sie das Benutzerkonto löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="43af0-178">The id of the compute node from which you want to delete the user account.</span></span></param>
        <param name="userName"><span data-ttu-id="43af0-179">Der Name des Benutzerkontos ein, das gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-179">The name of the user account to be deleted.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-180">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-180">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-181">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-181">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-182">Löscht das angegebene Benutzerkonto aus dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-182">Deletes the specified user account from the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-183">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-183">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-184">Sie können die Löschen eines Benutzerkontos nur, wenn diese wird von einem Serverknoten die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-184">You can delete a user account from a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="43af0-185">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-185">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFile">
      <MemberSignature Language="C#" Value="public void DeleteNodeFile (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNodeFile(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFile(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFile : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteNodeFile (poolId, computeNodeId, filePath, recursive, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-186">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-186">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-187">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-187">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="43af0-188">Der Pfad der zu löschenden Datei.</span><span class="sxs-lookup"><span data-stu-id="43af0-188">The path of the file to delete.</span></span></param>
        <param name="recursive">
            <span data-ttu-id="43af0-189">Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen.</span><span class="sxs-lookup"><span data-stu-id="43af0-189">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="43af0-190">Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="43af0-190">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-191">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-191">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-192">Löscht die angegebene Datei aus dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-192">Deletes the specified file from the specified compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="43af0-193">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-193">This is a blocking operation.</span></span>  <span data-ttu-id="43af0-194">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-194">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNodeFileAsync (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNodeFileAsync(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFileAsync : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteNodeFileAsync (poolId, computeNodeId, filePath, recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-195">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-195">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-196">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-196">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="43af0-197">Der Pfad der zu löschenden Datei.</span><span class="sxs-lookup"><span data-stu-id="43af0-197">The path of the file to delete.</span></span></param>
        <param name="recursive">
            <span data-ttu-id="43af0-198">Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen.</span><span class="sxs-lookup"><span data-stu-id="43af0-198">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="43af0-199">Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="43af0-199">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-200">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-200">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-201">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-201">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-202">Löscht die angegebene Datei aus dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-202">Deletes the specified file from the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-203">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-203">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="43af0-204">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-204">The delete operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePool">
      <MemberSignature Language="C#" Value="public void DeletePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeletePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeletePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeletePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeletePool (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-205">Die Id der dem zu löschenden Ressourcenpools an.</span><span class="sxs-lookup"><span data-stu-id="43af0-205">The id of the pool to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-206">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-206">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-207">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-207">Deletes the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-208">Der Löschvorgang fordert, dass der Pool gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-208">The delete operation requests that the pool be deleted.</span></span>  <span data-ttu-id="43af0-209">Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-209">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> state.</span></span>
            <span data-ttu-id="43af0-210">Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="43af0-210">The Batch service will requeue any running tasks and perform the actual pool deletion without any further client action.</span></span></para>
          <remarks><span data-ttu-id="43af0-211">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-211">This is a blocking operation.</span></span> <span data-ttu-id="43af0-212">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-212">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeletePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DeletePoolAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-213">Die Id der dem zu löschenden Ressourcenpools an.</span><span class="sxs-lookup"><span data-stu-id="43af0-213">The id of the pool to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-214">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-214">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-215">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-215">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-216">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-216">Deletes the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-217">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-217">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-218">Der Löschvorgang fordert, dass der Pool gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-218">The delete operation requests that the pool be deleted.</span></span>  <span data-ttu-id="43af0-219">Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-219">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> state.</span></span>
            <span data-ttu-id="43af0-220">Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="43af0-220">The Batch service will requeue any running tasks and perform the actual pool deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="43af0-221">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-221">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public void DisableAutoScale (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableAutoScale(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScale(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableAutoScale (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScale : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableAutoScale (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-222">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-222">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-223">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-223">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-224">Deaktiviert die automatische Skalierung für den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-224">Disables automatic scaling on the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-225">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-225">This is a blocking operation.</span></span> <span data-ttu-id="43af0-226">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-226">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAutoScaleAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAutoScaleAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScaleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableAutoScaleAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DisableAutoScaleAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-227">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-227">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-228">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-228">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-229">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-229">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-230">Deaktiviert die automatische Skalierung für den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-230">Disables automatic scaling on the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-231">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-231">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-232">Der Deaktivierungsvorgang für die automatische Skalierung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-232">The disable autoscale operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void DisableComputeNodeScheduling (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableComputeNodeScheduling(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeScheduling(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableComputeNodeScheduling (poolId As String, computeNodeId As String, disableComputeNodeSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption), Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeScheduling : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableComputeNodeScheduling (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-233">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-233">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-234">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-234">The id of the compute node.</span></span></param>
        <param name="disableComputeNodeSchedulingOption"><span data-ttu-id="43af0-235">Gibt an, was mit den derzeit ausgeführten Tasks.</span><span class="sxs-lookup"><span data-stu-id="43af0-235">Specifies what to do with currently running tasks.</span></span> <span data-ttu-id="43af0-236">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-236">The default is <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-237">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-237">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-238">Deaktiviert die aufgabenplanung auf dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-238">Disables task scheduling on the specified compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="43af0-239">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-239">This is a blocking operation.</span></span> <span data-ttu-id="43af0-240">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-240">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeSchedulingAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableComputeNodeSchedulingAsync (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-241">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-241">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-242">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-242">The id of the compute node.</span></span></param>
        <param name="disableComputeNodeSchedulingOption"><span data-ttu-id="43af0-243">Gibt an, was mit den derzeit ausgeführten Tasks.</span><span class="sxs-lookup"><span data-stu-id="43af0-243">Specifies what to do with currently running tasks.</span></span> <span data-ttu-id="43af0-244">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-244">The default is <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-245">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-245">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-246">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-246">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-247">Deaktiviert die aufgabenplanung auf dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-247">Disables task scheduling on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-248">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-248">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="43af0-249">Dieser Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-249">This operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public void EnableAutoScale (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableAutoScale(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableAutoScale (poolId As String, Optional autoscaleFormula As String = null, Optional autoscaleEvaluationInterval As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableAutoScale (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-250">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-250">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="43af0-251">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-251">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoscaleEvaluationInterval"><span data-ttu-id="43af0-252">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-252">The time interval at which to automatically adjust the pool size according to the AutoScale formula.</span></span> <span data-ttu-id="43af0-253">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-253">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-254">Der minimal zulässige Wert beträgt 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-254">The minimum allowed value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-255">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-255">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-256">Ermöglicht die automatische Skalierung für den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-256">Enables automatic scaling on the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-257">Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-257">The formula is checked for validity before it is applied to the pool.</span></span> <span data-ttu-id="43af0-258">Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</span><span class="sxs-lookup"><span data-stu-id="43af0-258">If the formula is not valid, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-259">Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-259">You cannot enable automatic scaling on a pool if a resize operation is in progress on the pool.</span></span></para>
          <para><span data-ttu-id="43af0-260">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-260">This is a blocking operation.</span></span> <span data-ttu-id="43af0-261">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-261">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAutoScaleAsync (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAutoScaleAsync(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScaleAsync : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableAutoScaleAsync (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EnableAutoScaleAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-262">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-262">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="43af0-263">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-263">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoscaleEvaluationInterval"><span data-ttu-id="43af0-264">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-264">The time interval at which to automatically adjust the pool size according to the AutoScale formula.</span></span> <span data-ttu-id="43af0-265">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-265">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-266">Der minimal zulässige Wert beträgt 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-266">The minimum allowed value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-267">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-267">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-268">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-268">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-269">Ermöglicht die automatische Skalierung für den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-269">Enables automatic scaling on the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-270">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-270">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-271">Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-271">The formula is checked for validity before it is applied to the pool.</span></span> <span data-ttu-id="43af0-272">Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</span><span class="sxs-lookup"><span data-stu-id="43af0-272">If the formula is not valid, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-273">Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-273">You cannot enable automatic scaling on a pool if a resize operation is in progress on the pool.</span></span></para>
          <para><span data-ttu-id="43af0-274">Der Vorgang zum Aktivieren der automatischen Skalierung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-274">The enable autoscale operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void EnableComputeNodeScheduling (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableComputeNodeScheduling(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableComputeNodeScheduling (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeScheduling : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableComputeNodeScheduling (poolId, computeNodeId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-275">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-275">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-276">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-276">The id of the compute node.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-277">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-277">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-278">Ermöglicht die aufgabenplanung auf dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-278">Enables task scheduling on the specified compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="43af0-279">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-279">This is a blocking operation.</span></span> <span data-ttu-id="43af0-280">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-280">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeSchedulingAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeSchedulingAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableComputeNodeSchedulingAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-281">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-281">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-282">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-282">The id of the compute node.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-283">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-283">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-284">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-284">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-285">Ermöglicht die aufgabenplanung auf dem angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-285">Enables task scheduling on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-286">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-286">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="43af0-287">Dieser Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-287">This operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScale(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function EvaluateAutoScale (poolId As String, autoscaleFormula As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScale : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.AutoScaleRun" Usage="poolOperations.EvaluateAutoScale (poolId, autoscaleFormula, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-288">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-288">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="43af0-289">Die Formel für den Pool ausgewertet werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-289">The formula to be evaluated on the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-290">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-290">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-291">Ruft das Ergebnis der Auswertung einer Automatisches Formel für den angegebenen Pool Skalierung.</span><span class="sxs-lookup"><span data-stu-id="43af0-291">Gets the result of evaluating an automatic scaling formula on the specified pool.</span></span>  <span data-ttu-id="43af0-292">Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-292">This is primarily for validating an autoscale formula, as it simply returns the result without applying the formula to the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-293">Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-293">The result of evaluating the <paramref name="autoscaleFormula" /> on the specified pool.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-294">Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-294">The formula is validated and its results calculated, but is not applied to the pool.</span></span>  <span data-ttu-id="43af0-295">Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-295">To apply the formula to the pool, use <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="43af0-296">Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-296">This method does not change any state of the pool, and does not affect the <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> or <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span></span></para>
          <para><span data-ttu-id="43af0-297">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-297">This is a blocking operation.</span></span> <span data-ttu-id="43af0-298">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-298">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScaleAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;" Usage="poolOperations.EvaluateAutoScaleAsync (poolId, autoscaleFormula, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EvaluateAutoScaleAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-299">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-299">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="43af0-300">Die Formel für den Pool ausgewertet werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-300">The formula to be evaluated on the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-301">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-301">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-302">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-302">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-303">Ruft das Ergebnis der Auswertung einer Automatisches Formel für den angegebenen Pool Skalierung.</span><span class="sxs-lookup"><span data-stu-id="43af0-303">Gets the result of evaluating an automatic scaling formula on the specified pool.</span></span>  <span data-ttu-id="43af0-304">Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-304">This is primarily for validating an autoscale formula, as it simply returns the result without applying the formula to the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-305">Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-305">The result of evaluating the <paramref name="autoscaleFormula" /> on the specified pool.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-306">Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-306">The formula is validated and its results calculated, but is not applied to the pool.</span></span>  <span data-ttu-id="43af0-307">Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-307">To apply the formula to the pool, use <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="43af0-308">Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-308">This method does not change any state of the pool, and does not affect the <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> or <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span></span></para>
          <para><span data-ttu-id="43af0-309">Die Evaluate-Vorgänge werden asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-309">The evaluate operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatistics(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLifetimeStatistics (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As PoolStatistics" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatistics : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.PoolStatistics" Usage="poolOperations.GetAllLifetimeStatistics additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-310">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-310">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-311">Zusammenfassung lebensdauerstatistiken für alle Pools im aktuellen Konto abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-311">Gets lifetime summary statistics for all of the pools in the current account.</span></span>  
            <span data-ttu-id="43af0-312">Statistiken werden für alle Pools aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="43af0-312">Statistics are aggregated across all pools that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-313">Die poolstatistiken der aggregierten.</span><span class="sxs-lookup"><span data-stu-id="43af0-313">The aggregated pool statistics.</span></span></returns>
        <remarks><span data-ttu-id="43af0-314">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-314">This is a blocking operation.</span></span> <span data-ttu-id="43af0-315">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-315">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatisticsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;" Usage="poolOperations.GetAllLifetimeStatisticsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetAllLifetimeStatisticsAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-316">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-316">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-317">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-317">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-318">Zusammenfassung lebensdauerstatistiken für alle Pools im aktuellen Konto abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-318">Gets lifetime summary statistics for all of the pools in the current account.</span></span>
            <span data-ttu-id="43af0-319">Statistiken werden für alle Pools aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="43af0-319">Statistics are aggregated across all pools that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-320">Die poolstatistiken der aggregierten.</span><span class="sxs-lookup"><span data-stu-id="43af0-320">The aggregated pool statistics.</span></span></returns>
        <remarks><span data-ttu-id="43af0-321">Der Abrufvorgang für die Statistik wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-321">The get statistics operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNode GetComputeNode (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNode GetComputeNode(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNode(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetComputeNode : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.ComputeNode" Usage="poolOperations.GetComputeNode (poolId, computeNodeId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-322">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-322">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-323">Die Id der Serverknoten aus dem Pool abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-323">The id of the compute node to get from the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="43af0-324">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-324">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-325">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-325">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-326">Ruft den angegebenen Computeknoten ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-326">Gets the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-327">Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-327">A <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> containing information about the specified compute node.</span></span></returns>
        <remarks><span data-ttu-id="43af0-328">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-328">This is a blocking operation.</span></span> <span data-ttu-id="43af0-329">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-329">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetComputeNodeAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.GetComputeNodeAsync (poolId, computeNodeId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-330">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-330">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-331">Die Id der Serverknoten aus dem Pool abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-331">The id of the compute node to get from the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="43af0-332">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-332">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-333">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-333">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-334">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-334">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-335">Ruft den angegebenen Computeknoten ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-335">Gets the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-336">Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-336">A <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> containing information about the specified compute node.</span></span></returns>
        <remarks><span data-ttu-id="43af0-337">Das Abrufen des Knotens wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-337">The get node operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="poolOperations.GetNodeFile (poolId, computeNodeId, filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-338">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-338">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-339">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-339">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="43af0-340">Der Pfad der Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-340">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-341">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-341">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-342">Ruft Informationen zu einer Datei auf einem Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="43af0-342">Gets information about a file on a compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-343">Ein <see cref="T:Microsoft.Azure.Batch.NodeFile" /> mit Informationen über die Datei und die zum Herunterladen der Datei verwendet werden können (siehe <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />).</span><span class="sxs-lookup"><span data-stu-id="43af0-343">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> containing information about the file, and which can be used to download the file (see <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />).</span></span></returns>
        <remarks><span data-ttu-id="43af0-344">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-344">This is a blocking operation.</span></span> <span data-ttu-id="43af0-345">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-345">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.GetNodeFileAsync (poolId, computeNodeId, filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-346">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-346">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-347">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-347">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="43af0-348">Der Pfad der Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-348">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-349">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-349">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-350">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-350">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-351">Ruft Informationen zu einer Datei auf einem Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="43af0-351">Gets information about a file on a compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-352">Ein <see cref="T:Microsoft.Azure.Batch.NodeFile" /> mit Informationen über die Datei und die zum Herunterladen der Datei verwendet werden können (siehe <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />).</span><span class="sxs-lookup"><span data-stu-id="43af0-352">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> containing information about the file, and which can be used to download the file (see <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />).</span></span></returns>
        <remarks><span data-ttu-id="43af0-353">Der Abrufvorgang für die Datei wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-353">The get file operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool GetPool (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool GetPool(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetPool : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.GetPool (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-354">Die Id der dem Pool abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-354">The id of the pool to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="43af0-355">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-355">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-356">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-356">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-357">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-357">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-358">Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> mit Informationen zu dem angegebenen Azure Batch-Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-358">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> containing information about the specified Azure Batch pool.</span></span></returns>
        <remarks><span data-ttu-id="43af0-359">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-359">This is a blocking operation.</span></span> <span data-ttu-id="43af0-360">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-360">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPoolAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.GetPoolAsync (poolId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetPoolAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-361">Die Id der dem Pool abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-361">The id of the pool to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="43af0-362">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-362">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-363">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-363">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-364">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-364">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-365">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-365">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-366">Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> mit Informationen zu dem angegebenen Azure Batch-Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-366">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> containing information about the specified Azure Batch pool.</span></span></returns>
        <remarks><span data-ttu-id="43af0-367">Die Get-Pool-Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-367">The get pool operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpStream As Stream, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpStream, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-368">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-368">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-369">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-369">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpStream"><span data-ttu-id="43af0-370">Die <see cref="T:System.IO.Stream" /> in dem Inhalt der RDP-Datei geschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-370">The <see cref="T:System.IO.Stream" /> into which the RDP file contents will be written.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-371">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-371">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-372">Ruft eine Datei (Remote Desktop Protocol, RDP) für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-372">Gets a Remote Desktop Protocol (RDP) file for the specified node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-373">Diese Methode schließt nicht die <paramref name="rdpStream" /> Stream und setzt nicht die Position nach dem Schreiben.</span><span class="sxs-lookup"><span data-stu-id="43af0-373">This method does not close the <paramref name="rdpStream" /> stream, and it does not reset the position after writing.</span></span>
            <span data-ttu-id="43af0-374">Der Verantwortung des Aufrufers den Stream geschlossen ist, oder um die Position zurückzusetzen, wenn erforderlich.</span><span class="sxs-lookup"><span data-stu-id="43af0-374">It is the caller's responsibility to close the stream, or to reset the position if required.</span></span></para>
          <para><span data-ttu-id="43af0-375">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-375">This is a blocking operation.</span></span> <span data-ttu-id="43af0-376">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-376">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="43af0-377">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="43af0-377">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="43af0-378">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="43af0-378">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="43af0-379">Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-379">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpFileNameToCreate As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-380">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-380">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-381">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-381">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpFileNameToCreate"><span data-ttu-id="43af0-382">Der Dateipfad, an dem die RDP-Datei erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-382">The file path at which to create the RDP file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-383">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-383">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-384">Ruft eine Remotedesktopprotokoll-Datei für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-384">Gets a Remote Desktop Protocol file for the specified node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-385">Wenn die Datei durch angegeben <paramref name="rdpFileNameToCreate" /> bereits vorhanden ist, wird Sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="43af0-385">If the file specified by <paramref name="rdpFileNameToCreate" /> already exists, it is overwritten.</span></span></para>
          <para><span data-ttu-id="43af0-386">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-386">This is a blocking operation.</span></span> <span data-ttu-id="43af0-387">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-387">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="43af0-388">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="43af0-388">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="43af0-389">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="43af0-389">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="43af0-390">Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-390">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpStream, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-391">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-391">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-392">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-392">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpStream"><span data-ttu-id="43af0-393">Die <see cref="T:System.IO.Stream" /> in dem Inhalt der RDP-Datei geschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-393">The <see cref="T:System.IO.Stream" /> into which the RDP file contents will be written.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-394">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-394">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-395">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-395">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-396">Ruft eine Datei (Remote Desktop Protocol, RDP) für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-396">Gets a Remote Desktop Protocol (RDP) file for the specified node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-397">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-397">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-398">Diese Methode schließt nicht die <paramref name="rdpStream" /> Stream und setzt nicht die Position nach dem Schreiben.</span><span class="sxs-lookup"><span data-stu-id="43af0-398">This method does not close the <paramref name="rdpStream" /> stream, and it does not reset the position after writing.</span></span>
            <span data-ttu-id="43af0-399">Der Verantwortung des Aufrufers den Stream geschlossen ist, oder um die Position zurückzusetzen, wenn erforderlich.</span><span class="sxs-lookup"><span data-stu-id="43af0-399">It is the caller's responsibility to close the stream, or to reset the position if required.</span></span></para>
          <para><span data-ttu-id="43af0-400">Der Abrufvorgang für RDP-Datei wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-400">The get RDP file operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="43af0-401">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="43af0-401">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="43af0-402">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="43af0-402">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="43af0-403">Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-403">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-404">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-404">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-405">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-405">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpFileNameToCreate"><span data-ttu-id="43af0-406">Der Dateipfad, an dem die RDP-Datei erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-406">The file path at which to create the RDP file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-407">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-407">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-408">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-408">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-409">Ruft eine Remotedesktopprotokoll-Datei für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="43af0-409">Gets a Remote Desktop Protocol file for the specified node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-410">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-410">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-411">Wenn die Datei durch angegeben <paramref name="rdpFileNameToCreate" /> bereits vorhanden ist, wird Sie überschrieben.</span><span class="sxs-lookup"><span data-stu-id="43af0-411">If the file specified by <paramref name="rdpFileNameToCreate" /> already exists, it is overwritten.</span></span></para>
          <para><span data-ttu-id="43af0-412">Der Abrufvorgang für RDP-Datei wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-412">The get RDP file operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="43af0-413">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="43af0-413">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="43af0-414">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="43af0-414">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="43af0-415">Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-415">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemoteLoginSettings (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As RemoteLoginSettings" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettings : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.RemoteLoginSettings" Usage="poolOperations.GetRemoteLoginSettings (poolId, computeNodeId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RemoteLoginSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-416">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-416">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-417">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-417">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-418">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-418">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-419">Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="43af0-419">Gets the settings required for remote login to a compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
          <para><span data-ttu-id="43af0-420">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-420">This is a blocking operation.</span></span> <span data-ttu-id="43af0-421">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-421">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="43af0-422">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="43af0-422">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property.</span></span> <span data-ttu-id="43af0-423">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="43af0-423">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="43af0-424">Für Anwendungspools mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> -Eigenschaft, eine der Methoden GetRDPFileAsync/GetRDPFile muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-424">For pools with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property, one of the GetRDPFileAsync/GetRDPFile methods must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettingsAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;" Usage="poolOperations.GetRemoteLoginSettingsAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-425">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-425">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-426">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="43af0-426">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-427">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-427">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-428">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-428">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-429">Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="43af0-429">Gets the settings required for remote login to a compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-430">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-430">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-431">Einstellungen für der Abrufvorgang-Remoteanmeldung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-431">The get remote login settings operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="43af0-432">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="43af0-432">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property.</span></span> <span data-ttu-id="43af0-433">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="43af0-433">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="43af0-434">Für Anwendungspools mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> -Eigenschaft, eine der Methoden GetRDPFileAsync/GetRDPFile muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-434">For pools with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property, one of the GetRDPFileAsync/GetRDPFile methods must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListComputeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListComputeNodes(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListComputeNodes : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.ListComputeNodes (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-435">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-435">The id of the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="43af0-436">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-436">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-437">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-437">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-438">Listet die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> des angegebenen Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-438">Enumerates the <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> of the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-439">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die asynchron oder synchron Auflisten von Computeknoten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="43af0-439">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate compute nodes asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="43af0-440">Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Knoten aus dem Batch-Dienst abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-440">This method returns immediately; the nodes are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="43af0-441">Datenabruf ist nicht atomaren; Knoten werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-441">Retrieval is non-atomic; nodes are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeAgentSkus(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeAgentSkus : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;" Usage="poolOperations.ListNodeAgentSkus (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="43af0-442">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-442">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-443">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-443">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-444">Listet die Knoten-Agent-Sku-Werte von Batch-Dienst unterstützt.</span><span class="sxs-lookup"><span data-stu-id="43af0-444">Enumerates the node agent Sku values supported by Batch Service.</span></span> 
            </summary>
        <returns><span data-ttu-id="43af0-445">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Knotenwerten-Agent-Sku synchron oder asynchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="43af0-445">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate node agent sku values asynchronously or synchronously.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (string poolId, string computeNodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeFiles(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.ListNodeFiles (poolId, computeNodeId, recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-446">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-446">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-447">Die Id des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="43af0-447">The id of the compute node.</span></span></param>
        <param name="recursive"><span data-ttu-id="43af0-448">Bei "true", listet rekursiv alle Dateien auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-448">If true, recursively enumerates all files on the compute node.</span></span> <span data-ttu-id="43af0-449">Wenn "false" listet nur die Dateien in das Stammverzeichnis der Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-449">If false, enumerates only the files in the compute node root directory.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="43af0-450">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-450">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-451">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-451">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-452">Listet Dateien auf den angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-452">Enumerates files on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-453">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Dateien asynchron oder synchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="43af0-453">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate files asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="43af0-454">Diese Methode gibt sofort zurück. die Daten einer Datei werden aus der Batch-Dienst abgerufen, nur, wenn die Auflistung aufgezählt wird.</span><span class="sxs-lookup"><span data-stu-id="43af0-454">This method returns immediately; the file data is retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="43af0-455">Datenabruf ist nicht atomaren; Dateidaten werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-455">Retrieval is non-atomic; file data is retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt; ListPools (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; ListPools(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPools : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.ListPools (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="43af0-456">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-456">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-457">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-457">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-458">Listet die <see cref="T:Microsoft.Azure.Batch.CloudPool">Pools</see> in dem Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="43af0-458">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudPool">pools</see> in the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-459">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Pools synchron oder asynchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="43af0-459">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate pools asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="43af0-460">Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Pools aus dem Batch-Dienst abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-460">This method returns immediately; the pools are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="43af0-461">Datenabruf ist nicht atomaren; Pools sind in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-461">Retrieval is non-atomic; pools are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPoolUsageMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPoolUsageMetrics(System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPoolUsageMetrics : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;" Usage="poolOperations.ListPoolUsageMetrics (startTime, endTime, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="43af0-462">Die Startzeit des aggregationsintervalls durch diesen Eintrag abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-462">The start time of the aggregation interval covered by this entry.</span></span></param>
        <param name="endTime"><span data-ttu-id="43af0-463">Die Endzeit des aggregationsintervalls für diesen Eintrag.</span><span class="sxs-lookup"><span data-stu-id="43af0-463">The end time of the aggregation interval for this entry.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="43af0-464">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-464">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-465">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-465">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-466">Listet die Nutzungsdaten Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-466">Enumerates pool usage metrics.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-467">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Metriken synchron oder asynchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="43af0-467">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate metrics asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="43af0-468">Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Metrikdaten aus der Batch-Dienst abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-468">This method returns immediately; the metrics data is retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="43af0-469">Datenabruf ist nicht atomaren; Metrikdaten werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="43af0-469">Retrieval is non-atomic; metrics data is retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public void Reboot (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reboot(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reboot(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reboot (poolId As String, computeNodeId As String, Optional rebootOption As Nullable(Of ComputeNodeRebootOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reboot : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reboot (poolId, computeNodeId, rebootOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-470">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-470">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-471">Die Id der Serverknoten neu starten.</span><span class="sxs-lookup"><span data-stu-id="43af0-471">The id of the compute node to reboot.</span></span></param>
        <param name="rebootOption"><span data-ttu-id="43af0-472">Gibt an, wann der Knoten neu starten und was mit den derzeit ausgeführten Tasks geschehen.</span><span class="sxs-lookup"><span data-stu-id="43af0-472">Specifies when to reboot the node and what to do with currently running tasks.</span></span> <span data-ttu-id="43af0-473">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-473">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-474">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-474">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-475">Startet die angegebene Serverknoten neu.</span><span class="sxs-lookup"><span data-stu-id="43af0-475">Reboots the specified compute node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-476">Sie können einen Serverknoten neu starten, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-476">You can reboot a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="43af0-477">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-477">This is a blocking operation.</span></span> <span data-ttu-id="43af0-478">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-478">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RebootAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RebootAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RebootAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RebootAsync (poolId, computeNodeId, rebootOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-479">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-479">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-480">Die Id der Serverknoten neu starten.</span><span class="sxs-lookup"><span data-stu-id="43af0-480">The id of the compute node to reboot.</span></span></param>
        <param name="rebootOption"><span data-ttu-id="43af0-481">Gibt an, wann der Knoten neu starten und was mit den derzeit ausgeführten Tasks geschehen.</span><span class="sxs-lookup"><span data-stu-id="43af0-481">Specifies when to reboot the node and what to do with currently running tasks.</span></span> <span data-ttu-id="43af0-482">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-482">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-483">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-483">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-484">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-484">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-485">Startet die angegebene Serverknoten neu.</span><span class="sxs-lookup"><span data-stu-id="43af0-485">Reboots the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-486">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-486">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-487">Sie können einen Serverknoten neu starten, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-487">You can reboot a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="43af0-488">Die Neustart-Vorgänge werden asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-488">The reboot operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reimage(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reimage(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage (poolId As String, computeNodeId As String, Optional reimageOption As Nullable(Of ComputeNodeReimageOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reimage : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reimage (poolId, computeNodeId, reimageOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-489">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-489">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-490">Die Id der Serverknoten zum reimaging.</span><span class="sxs-lookup"><span data-stu-id="43af0-490">The id of the compute node to reimage.</span></span></param>
        <param name="reimageOption"><span data-ttu-id="43af0-491">Gibt an, wann den Knoten ein reimaging durchführen und was mit den derzeit ausgeführten Tasks geschehen.</span><span class="sxs-lookup"><span data-stu-id="43af0-491">Specifies when to reimage the node and what to do with currently running tasks.</span></span> <span data-ttu-id="43af0-492">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-492">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-493">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-493">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-494">Neuinstallation des Betriebssystems auf den angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-494">Reinstalls the operating system on the specified compute node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-495">Compute-Knoten können erstellt werden, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-495">You can reimage a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="43af0-496">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-496">This is a blocking operation.</span></span> <span data-ttu-id="43af0-497">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-497">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReimageAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReimageAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ReimageAsync (poolId, computeNodeId, reimageOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-498">Die Id des Pools, den Compute-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="43af0-498">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-499">Die Id der Serverknoten zum reimaging.</span><span class="sxs-lookup"><span data-stu-id="43af0-499">The id of the compute node to reimage.</span></span></param>
        <param name="reimageOption"><span data-ttu-id="43af0-500">Gibt an, wann den Knoten ein reimaging durchführen und was mit den derzeit ausgeführten Tasks geschehen.</span><span class="sxs-lookup"><span data-stu-id="43af0-500">Specifies when to reimage the node and what to do with currently running tasks.</span></span> <span data-ttu-id="43af0-501">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-501">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-502">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-502">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-503">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-503">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-504">Neuinstallation des Betriebssystems auf den angegebenen Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="43af0-504">Reinstalls the operating system on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-505">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-505">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-506">Compute-Knoten können erstellt werden, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="43af0-506">You can reimage a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="43af0-507">Das reimaging-Vorgänge werden asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-507">The reimage operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-508">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-508">The id of the pool.</span></span></param>
        <param name="computeNode"><span data-ttu-id="43af0-509">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-509">The <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-510">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-510">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-511">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-511">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-512">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-512">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-513">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-513">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-514">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-514">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-515">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-515">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-516">Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-516">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-517">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="43af0-517">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> overload.</span></span></para>
          <para><span data-ttu-id="43af0-518">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-518">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-519">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-519">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-520">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-520">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-521">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-521">This is a blocking operation.</span></span> <span data-ttu-id="43af0-522">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-522">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodes As IEnumerable(Of ComputeNode), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-523">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-523">The id of the pool.</span></span></param>
        <param name="computeNodes"><span data-ttu-id="43af0-524">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-524">The <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-525">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-525">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-526">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-526">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-527">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-527">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-528">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-528">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-529">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-529">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-530">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-530">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-531">Entfernt die angegebene Serverknoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-531">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-532">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-532">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-533">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-533">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-534">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-534">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-535">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-535">This is a blocking operation.</span></span> <span data-ttu-id="43af0-536">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-536">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeIds As IEnumerable(Of String), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-537">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-537">The id of the pool.</span></span></param>
        <param name="computeNodeIds"><span data-ttu-id="43af0-538">Die Ids der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-538">The ids of the compute nodes to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-539">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-539">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-540">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-540">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-541">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-541">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-542">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-542">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-543">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-543">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-544">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-544">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-545">Entfernt die angegebene Serverknoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-545">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-546">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-546">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-547">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-547">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-548">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-548">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-549">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-549">This is a blocking operation.</span></span> <span data-ttu-id="43af0-550">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-550">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-551">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-551">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-552">Die Id der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-552">The id of the compute node to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-553">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-553">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-554">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-554">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-555">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-555">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-556">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-556">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-557">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-557">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-558">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-558">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-559">Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-559">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-560">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="43af0-560">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> overload.</span></span></para>
          <para><span data-ttu-id="43af0-561">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-561">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-562">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-562">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-563">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-563">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-564">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-564">This is a blocking operation.</span></span> <span data-ttu-id="43af0-565">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-565">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-566">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-566">The id of the pool.</span></span></param>
        <param name="computeNode"><span data-ttu-id="43af0-567">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-567">The <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-568">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-568">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-569">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-569">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-570">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-570">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-571">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-571">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-572">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-572">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-573">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-573">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-574">Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-574">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-575">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-575">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-576">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="43af0-576">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> overload.</span></span></para>
          <para><span data-ttu-id="43af0-577">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-577">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-578">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-578">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-579">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-579">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-580">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-580">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveFromPoolAsync (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-581">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-581">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="43af0-582">Die Id der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-582">The id of the compute node to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-583">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-583">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-584">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-584">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-585">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-585">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-586">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-586">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-587">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-587">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-588">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-588">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-589">Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-589">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-590">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-590">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-591">Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</span><span class="sxs-lookup"><span data-stu-id="43af0-591">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> overload.</span></span></para>
          <para><span data-ttu-id="43af0-592">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-592">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-593">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-593">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-594">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-594">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-595">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-595">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;RemoveFromPoolAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-596">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-596">The id of the pool.</span></span></param>
        <param name="computeNodes"><span data-ttu-id="43af0-597">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-597">The <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-598">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-598">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-599">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-599">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-600">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-600">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-601">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-601">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-602">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-602">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-603">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-603">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-604">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-604">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-605">Entfernt die angegebene Serverknoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-605">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-606">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-606">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-607">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-607">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-608">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-608">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-609">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-609">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-610">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-610">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-611">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-611">The id of the pool.</span></span></param>
        <param name="computeNodeIds"><span data-ttu-id="43af0-612">Die Ids der Serverknoten aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-612">The ids of the compute nodes to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-613">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="43af0-613">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="43af0-614">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-614">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-615">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an.</span><span class="sxs-lookup"><span data-stu-id="43af0-615">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-616">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-616">The default value is 15 minutes.</span></span> <span data-ttu-id="43af0-617">Der Mindestwert ist 5 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-617">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-618">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-618">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-619">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-619">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-620">Entfernt die angegebene Serverknoten aus dem angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-620">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-621">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-621">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-622">Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-622">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="43af0-623">Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-623">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="43af0-624">Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-624">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="43af0-625">Der Entfernungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-625">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePool">
      <MemberSignature Language="C#" Value="public void ResizePool (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResizePool(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePool(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResizePool (poolId As String, Optional targetDedicatedComputeNodes As Nullable(Of Integer) = null, Optional targetLowPriorityComputeNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ResizePool : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ResizePool (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-626">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-626">The id of the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="43af0-627">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-627">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-628">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="43af0-628">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="43af0-629">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-629">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-630">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="43af0-630">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-631">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-631">The timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-632">Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet.</span><span class="sxs-lookup"><span data-stu-id="43af0-632">If the pool has not reached the target size after this time, the resize is stopped.</span></span> <span data-ttu-id="43af0-633">Der Standardwert ist 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-633">The default is 15 minutes.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-634">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-634">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool, if the pool size is decreasing.</span></span> <span data-ttu-id="43af0-635">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-635">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-636">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-636">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-637">Ändert die Größe des angegebenen Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-637">Resizes the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="43af0-638">Die Größenänderung fordert, dass der Pool Größe geändert werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-638">The resize operation requests that the pool be resized.</span></span>  <span data-ttu-id="43af0-639">Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.</span><span class="sxs-lookup"><span data-stu-id="43af0-639">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> allocation state.</span></span>
            <span data-ttu-id="43af0-640">Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-640">The Batch service will perform the actual resize without any further client action, and set the allocation state to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> once complete.</span></span></para>
          <para>
            <span data-ttu-id="43af0-641">Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-641">You can only resize a pool when its <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            <span data-ttu-id="43af0-642">Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").</span><span class="sxs-lookup"><span data-stu-id="43af0-642">You cannot resize pools which are configured for automatic scaling (that is, the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> property of the pool is true).</span></span>
            <span data-ttu-id="43af0-643">Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-643">If you decrease the pool size, the Batch service chooses which nodes to remove.</span></span>  <span data-ttu-id="43af0-644">Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-644">To remove specific nodes, call <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="43af0-645">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-645">This is a blocking operation.</span></span> <span data-ttu-id="43af0-646">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-646">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResizePoolAsync (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResizePoolAsync(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResizePoolAsync : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ResizePoolAsync (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-647">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-647">The id of the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="43af0-648">Die gewünschte Anzahl von dedizierten Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-648">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-649">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="43af0-649">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="43af0-650">Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-650">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="43af0-651">Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.</span><span class="sxs-lookup"><span data-stu-id="43af0-651">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="43af0-652">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool.</span><span class="sxs-lookup"><span data-stu-id="43af0-652">The timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span> <span data-ttu-id="43af0-653">Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet.</span><span class="sxs-lookup"><span data-stu-id="43af0-653">If the pool has not reached the target size after this time, the resize is stopped.</span></span> <span data-ttu-id="43af0-654">Der Standardwert ist 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="43af0-654">The default is 15 minutes.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="43af0-655">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-655">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool, if the pool size is decreasing.</span></span> <span data-ttu-id="43af0-656">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-656">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-657">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-657">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-658">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-658">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-659">Ändert die Größe des angegebenen Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-659">Resizes the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-660">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-660">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="43af0-661">Die Größenänderung fordert, dass der Pool Größe geändert werden.</span><span class="sxs-lookup"><span data-stu-id="43af0-661">The resize operation requests that the pool be resized.</span></span>  <span data-ttu-id="43af0-662">Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.</span><span class="sxs-lookup"><span data-stu-id="43af0-662">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> allocation state.</span></span>
            <span data-ttu-id="43af0-663">Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</span><span class="sxs-lookup"><span data-stu-id="43af0-663">The Batch service will perform the actual resize without any further client action, and set the allocation state to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> once complete.</span></span></para>
          <para>
            <span data-ttu-id="43af0-664">Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-664">You can only resize a pool when its <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            <span data-ttu-id="43af0-665">Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").</span><span class="sxs-lookup"><span data-stu-id="43af0-665">You cannot resize pools which are configured for automatic scaling (that is, the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> property of the pool is true).</span></span>
            <span data-ttu-id="43af0-666">Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="43af0-666">If you decrease the pool size, the Batch service chooses which nodes to remove.</span></span>  <span data-ttu-id="43af0-667">Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-667">To remove specific nodes, call <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            </para>
          <para><span data-ttu-id="43af0-668">Die Größenänderung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="43af0-668">The resize operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePool">
      <MemberSignature Language="C#" Value="public void StopResizePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void StopResizePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopResizePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.StopResizePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.StopResizePool (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-669">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-669">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-670">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-670">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-671">Beendet einen Pool Größenänderungsvorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-671">Stops a pool resize operation.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-672">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-672">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="43af0-673">Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.</span><span class="sxs-lookup"><span data-stu-id="43af0-673">This operation stops an ongoing resize operation on the pool.</span></span>  <span data-ttu-id="43af0-674">Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="43af0-674">The pool size will stabilize at the number of nodes it is at when the stop operation is done.</span></span>  <span data-ttu-id="43af0-675">Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-675">During the stop operation, the pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes first to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> and then to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            </para>
          <para><span data-ttu-id="43af0-676">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="43af0-676">This is a blocking operation.</span></span> <span data-ttu-id="43af0-677">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-677">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopResizePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopResizePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopResizePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.StopResizePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="43af0-678">Die ID des Pools.</span><span class="sxs-lookup"><span data-stu-id="43af0-678">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="43af0-679">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-679">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="43af0-680">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-680">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="43af0-681">Beendet einen Pool Größenänderungsvorgangs.</span><span class="sxs-lookup"><span data-stu-id="43af0-681">Stops a pool resize operation.</span></span>
            </summary>
        <returns><span data-ttu-id="43af0-682">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="43af0-682">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="43af0-683">Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.</span><span class="sxs-lookup"><span data-stu-id="43af0-683">This operation stops an ongoing resize operation on the pool.</span></span>  <span data-ttu-id="43af0-684">Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="43af0-684">The pool size will stabilize at the number of nodes it is at when the stop operation is done.</span></span>  <span data-ttu-id="43af0-685">Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span><span class="sxs-lookup"><span data-stu-id="43af0-685">During the stop operation, the pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes first to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> and then to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            </para>
          <para><span data-ttu-id="43af0-686">Zum Beenden der Größe Vorgang führt asynchron aus.</span><span class="sxs-lookup"><span data-stu-id="43af0-686">The stop resize operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>