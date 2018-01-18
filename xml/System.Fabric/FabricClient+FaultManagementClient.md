<Type Name="FabricClient+FaultManagementClient" FullName="System.Fabric.FabricClient+FaultManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.FaultManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/FaultManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.FaultManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.FaultManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.FaultManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="355e7-101">Stellt Funktionen zum Einfügen von Fehlern in einem Service Fabric-Cluster bereit.</span><span class="sxs-lookup"><span data-stu-id="355e7-101">Provides functionality to introduce faults in a Service Fabric cluster.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-102">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-102">Move primary will be called on this Selected Partition.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-103">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-103">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-104">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-104">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-105">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-105">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="355e7-106">Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-106">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="355e7-107">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-107">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-108">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-108">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-109">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-109">Invalid operation</span></span>
            - <span data-ttu-id="355e7-110">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-110">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-111">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-111">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-112">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-112">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-113">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-113">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-114">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-114">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-115">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-115">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-116">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-116">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-117">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-117">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="355e7-118">Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-118">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="355e7-119">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-119">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-120">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-120">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-121">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-121">Invalid operation</span></span>
            - <span data-ttu-id="355e7-122">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-122">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-123">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-123">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-124">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-124">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-125">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-125">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-126">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-126">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-127">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-127">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-128">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-128">A task with move primary result</span></span></returns>
        <remarks><span data-ttu-id="355e7-129">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-129">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="355e7-130">Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-130">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="355e7-131">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-131">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-132">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-132">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-133">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-133">Invalid operation</span></span>
            - <span data-ttu-id="355e7-134">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-134">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-135">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-135">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-136">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-136">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-137">Knoten zu benennen, wobei primären Replikat verschoben werden soll</span><span class="sxs-lookup"><span data-stu-id="355e7-137">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-138">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-138">Move primary will be called on this Selected Partition.</span></span> </param>
        <summary>
            <span data-ttu-id="355e7-139">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-139">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-140">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-140">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-141">-API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.</span><span class="sxs-lookup"><span data-stu-id="355e7-141">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
            <span data-ttu-id="355e7-142">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-142">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-143">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-143">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-144">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-144">Invalid operation</span></span>
            - <span data-ttu-id="355e7-145">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-145">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-146">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-146">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-147">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-147">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-148">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-148">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-149">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-149">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-150">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-150">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-151">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-151">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-152">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-152">A task with move primary result</span></span></returns>
        <remarks><span data-ttu-id="355e7-153">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-153">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="355e7-154">Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-154">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="355e7-155">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-155">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-156">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-156">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-157">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-157">Invalid operation</span></span>
            - <span data-ttu-id="355e7-158">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-158">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-159">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-159">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-160">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-160">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-161">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-161">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-162">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-162">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-163">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-163">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-164">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-164">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-165">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-165">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-166">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-166">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="355e7-167">Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-167">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="355e7-168">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-168">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-169">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-169">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-170">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-170">Invalid operation</span></span>
            - <span data-ttu-id="355e7-171">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-171">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-172">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-172">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-173">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-173">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-174">Knoten zu benennen, wobei primären Replikat verschoben werden soll</span><span class="sxs-lookup"><span data-stu-id="355e7-174">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-175">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-175">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-176">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-176">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
             <span data-ttu-id="355e7-177">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-177">Moves selected primary replica to new node in the cluster.</span></span>
             </summary>
        <returns><span data-ttu-id="355e7-178">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-178">A task with move primary result</span></span></returns>
        <remarks>
             <span data-ttu-id="355e7-179">-API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.</span><span class="sxs-lookup"><span data-stu-id="355e7-179">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
             <span data-ttu-id="355e7-180">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-180">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
             </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-181">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-181">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-182">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-182">Invalid operation</span></span>
             - <span data-ttu-id="355e7-183">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-183">If action called on stateless service.</span></span>
             - <span data-ttu-id="355e7-184">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-184">If not enough nodes available for action</span></span>
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             <span data-ttu-id="355e7-185">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-185">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-186">Knoten zu benennen, wobei primären Replikat verschoben werden soll</span><span class="sxs-lookup"><span data-stu-id="355e7-186">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-187">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-187">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="token"><span data-ttu-id="355e7-188">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-188">The cancellation token</span></span></param>
        <summary>
             <span data-ttu-id="355e7-189">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-189">Moves selected primary replica to new node in the cluster.</span></span>
             </summary>
        <returns><span data-ttu-id="355e7-190">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-190">A task with move primary result</span></span></returns>
        <remarks>
             <span data-ttu-id="355e7-191">-API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.</span><span class="sxs-lookup"><span data-stu-id="355e7-191">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
             <span data-ttu-id="355e7-192">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-192">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
             </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-193">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-193">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-194">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-194">Invalid operation</span></span>
             - <span data-ttu-id="355e7-195">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-195">If action called on stateless service.</span></span>
             - <span data-ttu-id="355e7-196">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-196">If not enough nodes available for action</span></span>
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             <span data-ttu-id="355e7-197">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-197">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-198">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-198">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-199">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-199">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-200">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-200">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-201">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-201">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-202">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-202">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-203">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-203">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-204">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-204">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="355e7-205">Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-205">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="355e7-206">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-206">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-207">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-207">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-208">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-208">Invalid operation</span></span>
            - <span data-ttu-id="355e7-209">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-209">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-210">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-210">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-211">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-211">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-212">Knoten zu benennen, wobei primären Replikat verschoben werden soll</span><span class="sxs-lookup"><span data-stu-id="355e7-212">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-213">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-213">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-214">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-214">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-215">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-215">The cancellation token</span></span></param>
        <summary>
             <span data-ttu-id="355e7-216">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-216">Moves selected primary replica to new node in the cluster.</span></span>
             </summary>
        <returns><span data-ttu-id="355e7-217">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-217">A task with move primary result</span></span></returns>
        <remarks>
             <span data-ttu-id="355e7-218">-API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.</span><span class="sxs-lookup"><span data-stu-id="355e7-218">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
             <span data-ttu-id="355e7-219">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-219">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
             </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-220">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-220">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-221">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-221">Invalid operation</span></span>
             - <span data-ttu-id="355e7-222">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-222">If action called on stateless service.</span></span>
             - <span data-ttu-id="355e7-223">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-223">If not enough nodes available for action</span></span>
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             <span data-ttu-id="355e7-224">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-224">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-225">Knoten zu benennen, wobei primären Replikat verschoben werden soll</span><span class="sxs-lookup"><span data-stu-id="355e7-225">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-226">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-226">Move primary will be called on this Selected Partition.</span></span>
            <span data-ttu-id="355e7-227">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-227">API uses the primary replica of the selected partition to move to new node location.</span></span>
            </param>
        <param name="operationTimeout"><span data-ttu-id="355e7-228">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-228">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-229">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-229">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-230">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-230">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-231">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-231">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-232">-API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.</span><span class="sxs-lookup"><span data-stu-id="355e7-232">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
            <span data-ttu-id="355e7-233">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-233">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-234">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-234">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-235">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-235">Invalid operation</span></span>
            - <span data-ttu-id="355e7-236">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-236">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-237">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-237">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-238">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-238">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-239">Knoten zu benennen, wobei primären Replikat verschoben werden soll</span><span class="sxs-lookup"><span data-stu-id="355e7-239">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-240">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-240">Move primary will be called on this Selected Partition.</span></span>
            <span data-ttu-id="355e7-241">-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.</span><span class="sxs-lookup"><span data-stu-id="355e7-241">API uses the primary replica of the selected partition to move to new node location.</span></span>
            </param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-242">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-242">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-243">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-243">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-244">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-244">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-245">Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-245">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-246">Eine Aufgabe mit primären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-246">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-247">-API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.</span><span class="sxs-lookup"><span data-stu-id="355e7-247">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
            <span data-ttu-id="355e7-248">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-248">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-249">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-249">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-250">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-250">Invalid operation</span></span>
            - <span data-ttu-id="355e7-251">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-251">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-252">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-252">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-253">FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.</span><span class="sxs-lookup"><span data-stu-id="355e7-253">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-254">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-254">Move Secondary will be called on this Selected Partition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="355e7-255">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-255">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-256">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-256">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-257">-API verwendet das ausgewählte sekundäre Replikat in Partitionsstruktur-Selektor angegebene vom aktuellen sekundären Knoten.</span><span class="sxs-lookup"><span data-stu-id="355e7-257">API uses the selected secondary replica inside partition selector structure specified by current secondary node.</span></span> <span data-ttu-id="355e7-258">Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-258">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-259">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-259">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-260">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-260">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-261">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-261">Invalid operation</span></span>
            - <span data-ttu-id="355e7-262">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-262">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-263">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-263">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-264">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-264">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-265">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-265">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-266">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-266">Move Secondary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-267">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-267">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-268">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-268">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-269">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-269">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-270">-API verwendet das ausgewählte sekundäre Replikat in Partitionsstruktur-Selektor angegebene vom aktuellen sekundären Knoten.</span><span class="sxs-lookup"><span data-stu-id="355e7-270">API uses the selected secondary replica inside partition selector structure specified by current secondary node.</span></span> <span data-ttu-id="355e7-271">Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-271">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-272">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-272">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-273">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-273">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-274">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-274">Invalid operation</span></span>
            - <span data-ttu-id="355e7-275">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-275">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-276">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-276">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-277">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-277">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-278">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-278">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-279">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-279">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-280">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-280">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-281">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-281">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-282">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-282">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-283">Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-283">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-284">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-284">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-285">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-285">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-286">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-286">Invalid operation</span></span>
            - <span data-ttu-id="355e7-287">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-287">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-288">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-288">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-289">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-289">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-290">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Replikat verschoben wird ist kein sekundärer FabricErrorCode.ConstraintNotSatisfied -, wenn die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-290">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the replica being moved is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-291">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-291">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-292">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-292">Move Secondary will be called on this Selected Partition.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-293">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-293">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-294">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-294">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="355e7-295">-API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur.</span><span class="sxs-lookup"><span data-stu-id="355e7-295">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="355e7-296">Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-296">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-297">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-297">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-298">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-298">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-299">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-299">Invalid operation</span></span>
            - <span data-ttu-id="355e7-300">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-300">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-301">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-301">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-302">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-302">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-303">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-303">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-304">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-304">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-305">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-305">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-306">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-306">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-307">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-307">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-308">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-308">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-309">Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-309">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-310">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-310">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-311">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-311">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-312">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-312">Invalid operation</span></span>
            - <span data-ttu-id="355e7-313">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-313">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-314">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-314">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-315">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-315">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-316">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Replikat verschoben wird ist kein sekundärer FabricErrorCode.ConstraintNotSatisfied -, wenn die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-316">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the replica being moved is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-317">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-317">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-318">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-318">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-319">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-319">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-320">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-320">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-321">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-321">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-322">-API verwendet das nach dem Zufallsprinzip ausgewählte sekundäre Replikat für angegebene Partition-Auswahl.</span><span class="sxs-lookup"><span data-stu-id="355e7-322">API uses the randomly selected secondary replica for specified partition selector.</span></span>
            <span data-ttu-id="355e7-323">Diese Überladung API wählt zufallsgesteuert neuen sekundären knotenspeicherort für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-323">This API overload randomly selects new secondary node location for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-324">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-324">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-325">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-325">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-326">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-326">Invalid operation</span></span>
            - <span data-ttu-id="355e7-327">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-327">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-328">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-328">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-329">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-329">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-330">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist</span><span class="sxs-lookup"><span data-stu-id="355e7-330">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-331">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-331">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-332">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-332">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-333">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-333">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-334">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-334">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-335">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-335">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="355e7-336">-API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur.</span><span class="sxs-lookup"><span data-stu-id="355e7-336">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="355e7-337">Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-337">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-338">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-338">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-339">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-339">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-340">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-340">Invalid operation</span></span>
            - <span data-ttu-id="355e7-341">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-341">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-342">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-342">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-343">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-343">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-344">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Replikat verschoben wird ist kein sekundärer FabricErrorCode.ConstraintNotSatisfied -, wenn die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-344">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the replica being moved is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-345">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-345">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-346">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-346">Move Secondary will be called on this Selected Partition.</span></span>
            </param>
        <param name="token"><span data-ttu-id="355e7-347">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-347">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-348">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-348">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-349">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-349">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-350">-API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur.</span><span class="sxs-lookup"><span data-stu-id="355e7-350">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="355e7-351">Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-351">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-352">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-352">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-353">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-353">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-354">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-354">Invalid operation</span></span>
            - <span data-ttu-id="355e7-355">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-355">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-356">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-356">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-357">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-357">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-358">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-358">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-359">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-359">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="355e7-360">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</span><span class="sxs-lookup"><span data-stu-id="355e7-360">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-361">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-361">Move Secondary will be called on this Selected Partition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="355e7-362">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-362">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-363">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-363">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-364">API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-364">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="355e7-365">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-365">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-366">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-366">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-367">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-367">Invalid operation</span></span>
            - <span data-ttu-id="355e7-368">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-368">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-369">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-369">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-370">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-370">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-371">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-371">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="355e7-372">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-372">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-373">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-373">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-374">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-374">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-375">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-375">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-376">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-376">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-377">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-377">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-378">-API verwendet das nach dem Zufallsprinzip ausgewählte sekundäre Replikat für angegebene Partition-Auswahl.</span><span class="sxs-lookup"><span data-stu-id="355e7-378">API uses the randomly selected secondary replica for specified partition selector.</span></span>
            <span data-ttu-id="355e7-379">Diese Überladung API wählt zufallsgesteuert neuen sekundären knotenspeicherort für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-379">This API overload randomly selects new secondary node location for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-380">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-380">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-381">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-381">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-382">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-382">Invalid operation</span></span>
            - <span data-ttu-id="355e7-383">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-383">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-384">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-384">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-385">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-385">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-386">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist</span><span class="sxs-lookup"><span data-stu-id="355e7-386">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-387">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-387">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-388">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-388">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-389">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-389">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-390">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-390">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-391">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-391">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-392">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-392">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-393">-API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur.</span><span class="sxs-lookup"><span data-stu-id="355e7-393">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="355e7-394">Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-394">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="355e7-395">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-395">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-396">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-396">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-397">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-397">Invalid operation</span></span>
            - <span data-ttu-id="355e7-398">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-398">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-399">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-399">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-400">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-400">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-401">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-401">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-402">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-402">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-403">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-403">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-404">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-404">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-405">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-405">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-406">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-406">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-407">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-407">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="355e7-408">-API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-408">API uses the selected secondary replica specified by currentNodeName.</span></span>
            <span data-ttu-id="355e7-409">Das ausgewählte Replikat wird an den nach dem Zufallsprinzip ausgewählten knotenspeicherort für neue verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-409">This selected replica will be moved to the randomly selected new node location.</span></span>
            <span data-ttu-id="355e7-410">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-410">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-411">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-411">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-412">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-412">Invalid operation</span></span>
            - <span data-ttu-id="355e7-413">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-413">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-414">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-414">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-415">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-415">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-416">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-416">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-417">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-417">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="355e7-418">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</span><span class="sxs-lookup"><span data-stu-id="355e7-418">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-419">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-419">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-420">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-420">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-421">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-421">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-422">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-422">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-423">API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-423">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="355e7-424">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-424">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-425">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-425">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-426">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-426">Invalid operation</span></span>
            - <span data-ttu-id="355e7-427">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-427">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-428">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-428">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-429">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-429">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-430">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-430">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-431">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-431">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="355e7-432">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</span><span class="sxs-lookup"><span data-stu-id="355e7-432">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-433">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-433">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-434">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-434">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-435">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-435">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-436">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-436">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-437">API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-437">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="355e7-438">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-438">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-439">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-439">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-440">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-440">Invalid operation</span></span>
            - <span data-ttu-id="355e7-441">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-441">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-442">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-442">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-443">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-443">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-444">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-444">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-445">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-445">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-446">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-446">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-447">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-447">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-448">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-448">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-449">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-449">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-450">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-450">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-451">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-451">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="355e7-452">-API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-452">API uses the selected secondary replica specified by currentNodeName.</span></span>
            <span data-ttu-id="355e7-453">Das ausgewählte Replikat wird an den nach dem Zufallsprinzip ausgewählten knotenspeicherort für neue verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-453">This selected replica will be moved to the randomly selected new node location.</span></span>
            <span data-ttu-id="355e7-454">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-454">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-455">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-455">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-456">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-456">Invalid operation</span></span>
            - <span data-ttu-id="355e7-457">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-457">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-458">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-458">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-459">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-459">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-460">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-460">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-461">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-461">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="355e7-462">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</span><span class="sxs-lookup"><span data-stu-id="355e7-462">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-463">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-463">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-464">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-464">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-465">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-465">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-466">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-466">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-467">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-467">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-468">API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-468">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="355e7-469">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-469">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-470">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-470">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-471">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-471">Invalid operation</span></span>
            - <span data-ttu-id="355e7-472">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-472">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-473">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-473">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-474">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-474">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-475">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist</span><span class="sxs-lookup"><span data-stu-id="355e7-475">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-476">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-476">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="355e7-477">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</span><span class="sxs-lookup"><span data-stu-id="355e7-477">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-478">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-478">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-479">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-479">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-480">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-480">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-481">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-481">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-482">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-482">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-483">-API verwendet das ausgewählte sekundäre Replikat in Selektor Partitionsstruktur nach CurrentNodeName Standort angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-483">API uses the selected secondary replica inside partition selector structure specified by currentNodeName location.</span></span> <span data-ttu-id="355e7-484">Das ausgewählte Replikat wird in NewNodeName Speicherort aus der aktuellen Position verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-484">This selected replica will be moved to newNodeName location from current node location.</span></span>
            <span data-ttu-id="355e7-485">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-485">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-486">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-486">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-487">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-487">Invalid operation</span></span>
            - <span data-ttu-id="355e7-488">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-488">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-489">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-489">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-490">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-490">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-491">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist</span><span class="sxs-lookup"><span data-stu-id="355e7-491">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="355e7-492">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-492">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="355e7-493">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</span><span class="sxs-lookup"><span data-stu-id="355e7-493">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="355e7-494">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-494">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="355e7-495">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="355e7-495">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-496">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-496">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-497">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="355e7-497">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-498">Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="355e7-498">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-499">Eine Aufgabe mit sekundären Ergebnis verschieben</span><span class="sxs-lookup"><span data-stu-id="355e7-499">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-500">-API verwendet das ausgewählte sekundäre Replikat in Selektor Partitionsstruktur nach CurrentNodeName Standort angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-500">API uses the selected secondary replica inside partition selector structure specified by currentNodeName location.</span></span> <span data-ttu-id="355e7-501">Das ausgewählte Replikat wird in NewNodeName Speicherort aus der aktuellen Position verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-501">This selected replica will be moved to newNodeName location from current node location.</span></span>
            <span data-ttu-id="355e7-502">Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-502">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-503">Versuchen Sie es erneut erschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-503">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-504">Ungültiger Vorgang</span><span class="sxs-lookup"><span data-stu-id="355e7-504">Invalid operation</span></span>
            - <span data-ttu-id="355e7-505">Wenn die Aktion für statusfreien Dienst aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="355e7-505">If action called on stateless service.</span></span>
            - <span data-ttu-id="355e7-506">Wenn kein aktives sekundäres Replikat vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-506">If no active secondary replica exists</span></span>
            - <span data-ttu-id="355e7-507">Wenn nicht genügend Knoten, die für die Aktion verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="355e7-507">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="355e7-508">FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist</span><span class="sxs-lookup"><span data-stu-id="355e7-508">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-509">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="355e7-509">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be removed.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-510">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der FM vie.w ist</span><span class="sxs-lookup"><span data-stu-id="355e7-510">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM vie.w</span></span></param>
        <param name="forceRemove"><span data-ttu-id="355e7-511">Das Replikat wird erzwungen entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-511">Will forcefully remove the replica</span></span></param>
        <summary>
            <span data-ttu-id="355e7-512">Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-512">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-513">Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-513">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-514">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-514">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-515">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-515">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-516">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-516">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-517">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="355e7-517">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be removed.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-518">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der Sicht FM ist</span><span class="sxs-lookup"><span data-stu-id="355e7-518">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM view</span></span></param>
        <param name="forceRemove"><span data-ttu-id="355e7-519">Das Replikat wird erzwungen entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-519">Will forcefully remove the replica</span></span></param>
        <param name="token"><span data-ttu-id="355e7-520">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-520">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-521">Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-521">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-522">Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-522">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-523">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-523">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-524">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-524">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-525">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-525">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-526">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="355e7-526">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be removed.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-527">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der Sicht FM ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-527">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM view.</span></span></param>
        <param name="forceRemove"><span data-ttu-id="355e7-528">Entfernt das Replikat erzwungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-528">Will forcefully remove the replica.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-529">Das gesamttimeout für den Vorgang, z. B. das Timeout für das Replikat entfernt werden soll, wenn warten <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</span><span class="sxs-lookup"><span data-stu-id="355e7-529">The overall timeout for the operation including the timeout to wait for replica to be removed if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="355e7-530">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-530">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-531">Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-531">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-532">Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-532">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-533">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-533">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-534">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-534">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-535">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-535">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-536">Name des Knotens, auf dem Replikat wird verschoben werden soll<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="355e7-536">Node name where replica is to be moved <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="355e7-537">Partitions-Id, in dem das Replikat muss entfernt werden</span><span class="sxs-lookup"><span data-stu-id="355e7-537">Partition Id where the replica needs to be removed</span></span> </param>
        <param name="replicaId"><span data-ttu-id="355e7-538">Replikat-Id, die entfernt werden muss</span><span class="sxs-lookup"><span data-stu-id="355e7-538">Replica Id that needs to be removed</span></span> </param>
        <param name="completionMode"><span data-ttu-id="355e7-539">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-539">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="forceRemove"><span data-ttu-id="355e7-540">Das Replikat wird erzwungen entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-540">Will forcefully remove the replica</span></span></param>
        <summary>
            <span data-ttu-id="355e7-541">Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-541">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-542">Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-542">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-543">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-543">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-544">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-544">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-545">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-545">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-546">Name des Knotens, auf dem Replikat wird verschoben werden soll<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="355e7-546">Node name where replica is to be moved <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="355e7-547">Partitions-Id, in dem das Replikat muss entfernt werden</span><span class="sxs-lookup"><span data-stu-id="355e7-547">Partition Id where the replica needs to be removed</span></span> </param>
        <param name="replicaId"><span data-ttu-id="355e7-548">Replikat-Id, die entfernt werden muss</span><span class="sxs-lookup"><span data-stu-id="355e7-548">Replica Id that needs to be removed</span></span> </param>
        <param name="completionMode"><span data-ttu-id="355e7-549">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der Sicht FM ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-549">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM view.</span></span></param>
        <param name="forceRemove"><span data-ttu-id="355e7-550">Das Replikat wird erzwungen entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-550">Will forcefully remove the replica</span></span></param>
        <param name="token"><span data-ttu-id="355e7-551">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-551">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-552">Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-552">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-553">Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-553">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-554">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-554">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-555">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-555">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-556">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-556">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-557">Name des Knotens, auf dem Replikat wird verschoben werden soll<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="355e7-557">Node name where replica is to be moved <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="355e7-558">Partitions-Id, in dem das Replikat muss entfernt werden</span><span class="sxs-lookup"><span data-stu-id="355e7-558">Partition Id where the replica needs to be removed</span></span> </param>
        <param name="replicaId"><span data-ttu-id="355e7-559">Replikat-Id, die entfernt werden muss</span><span class="sxs-lookup"><span data-stu-id="355e7-559">Replica Id that needs to be removed</span></span> </param>
        <param name="completionMode"><span data-ttu-id="355e7-560">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-560">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="forceRemove"><span data-ttu-id="355e7-561">Entfernt das Replikat erzwungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-561">Will forcefully remove the replica.</span></span></param>
        <param name="operationTimeoutSec"><span data-ttu-id="355e7-562">Das allgemeine Timeout in Sekunden für den Vorgang, z. B. das Timeout warten Replikat entfernt werden soll, wenn <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</span><span class="sxs-lookup"><span data-stu-id="355e7-562">The overall timeout in seconds for the operation, including the timeout to wait for replica to be removed if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="355e7-563">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-563">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-564">Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-564">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-565">Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-565">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-566">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-566">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-567">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-567">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-568">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-568">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="355e7-569">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-569">The name of the application to which the code package belongs</span></span></param>
        <param name="replicaSelector"><span data-ttu-id="355e7-570">Die <see cref="T:System.Fabric.ReplicaSelector" /> identifiziert das Replikat, dessen Codepaket Host muss neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-570">The <see cref="T:System.Fabric.ReplicaSelector" /> which identifies the replica whose host code package needs to be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-571">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-571">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-572">Dieser API-Aufruf neu gestartet, wird das Codepaket hostet das Replikat gemäß der <see cref="T:System.Fabric.ReplicaSelector" /> und der angegebene Anwendungsname gehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-572">This API call restarts the code package which hosts the replica specified by the <see cref="T:System.Fabric.ReplicaSelector" /> and belongs to the specified application name.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-573">RestartDeployedCodePackageResult die Informationen zu den eigentlichen Codepaket neu gestartet und das Replikat ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="355e7-573">RestartDeployedCodePackageResult which gives information about the actual code package restarted and replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-574">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-574">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-575">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-575">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-576">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-576">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-577">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist - Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde, – wenn die angegebene Partition ausgewählt nicht FabricErrorCode.CodePackageNotFound vorhanden ist – wenn die ausgewählten Code Paket wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="355e7-577">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist FabricErrorCode.CodePackageNotFound - If the selected code package was not found</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-578">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-578">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="355e7-579">Der Name der Anwendung zu dem Paket der Code belong.s</span><span class="sxs-lookup"><span data-stu-id="355e7-579">The name of the application to which the code package belong.s</span></span></param>
        <param name="replicaSelector"><span data-ttu-id="355e7-580">Die <see cref="T:System.Fabric.ReplicaSelector" /> identifiziert das Replikat, dessen Codepaket Host muss neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-580">The <see cref="T:System.Fabric.ReplicaSelector" /> which identifies the replica whose host code package needs to be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-581">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-581">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-582">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-582">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-583">Dieser API-Aufruf neu gestartet, wird das Codepaket hostet das Replikat gemäß der <see cref="T:System.Fabric.ReplicaSelector" /> und der angegebene Anwendungsname gehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-583">This API call restarts the code package which hosts the replica specified by the <see cref="T:System.Fabric.ReplicaSelector" /> and belongs to the specified application name.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-584">RestartDeployedCodePackageResult die Informationen zu den eigentlichen Codepaket neu gestartet und das Replikat ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="355e7-584">RestartDeployedCodePackageResult which gives information about the actual code package restarted and replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-585">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-585">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-586">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-586">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-587">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-587">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-588">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist - Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde, – wenn die angegebene Partition ausgewählt nicht FabricErrorCode.CodePackageNotFound vorhanden ist – wenn die ausgewählten Code Paket wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="355e7-588">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist FabricErrorCode.CodePackageNotFound - If the selected code package was not found.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-589">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-589">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="355e7-590">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-590">The name of the application to which the code package belongs</span></span></param>
        <param name="replicaSelector"><span data-ttu-id="355e7-591">Die <see cref="T:System.Fabric.ReplicaSelector" /> identifiziert das Replikat, dessen Codepaket Host muss neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-591">The <see cref="T:System.Fabric.ReplicaSelector" /> which identifies the replica whose host code package needs to be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-592">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Code-Pakets abgeschlossen ist oder not.n</span><span class="sxs-lookup"><span data-stu-id="355e7-592">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.n</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-593">Das gesamttimeout für den Vorgang, z. B. das Timeout warten Codepaket wenn Neustart <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</span><span class="sxs-lookup"><span data-stu-id="355e7-593">The overall timeout for the operation including the timeout to wait for code package to restart if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="355e7-594">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="355e7-594">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-595">Dieser API-Aufruf neu gestartet, wird das Codepaket hostet das Replikat gemäß der <see cref="T:System.Fabric.ReplicaSelector" /> und der angegebene Anwendungsname gehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-595">This API call restarts the code package which hosts the replica specified by the <see cref="T:System.Fabric.ReplicaSelector" /> and belongs to the specified application name.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-596">RestartDeployedCodePackageResult die Informationen zu den eigentlichen Codepaket neu gestartet und das Replikat ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="355e7-596">RestartDeployedCodePackageResult which gives information about the actual code package restarted and replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-597">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-597">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-598">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-598">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-599">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-599">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-600">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist - Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde, – wenn die angegebene Partition ausgewählt nicht FabricErrorCode.CodePackageNotFound vorhanden ist – wenn die ausgewählten Code Paket wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="355e7-600">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist FabricErrorCode.CodePackageNotFound - If the selected code package was not found</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-601">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-601">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-602">Der Knoten, auf dem das Codepaket gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-602">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="355e7-603">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-603">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="355e7-604">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-604">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="codePackageName"><span data-ttu-id="355e7-605">Der Name des Pakets Code neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-605">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="355e7-606">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-606">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-607">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-607">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-608">Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-608">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-609">RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-609">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="355e7-610">SelectedReplica ist keine in dieser Überladung.</span><span class="sxs-lookup"><span data-stu-id="355e7-610">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-611">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-611">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-612">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-612">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-613">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-613">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-614">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</span><span class="sxs-lookup"><span data-stu-id="355e7-614">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-615">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-615">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-616">Der Knoten, auf dem das Codepaket gehostet wird</span><span class="sxs-lookup"><span data-stu-id="355e7-616">The node on which the code package is hosted</span></span></param>
        <param name="applicationName"><span data-ttu-id="355e7-617">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-617">The name of the application to which the code package belongs</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="355e7-618">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist</span><span class="sxs-lookup"><span data-stu-id="355e7-618">The name of the service manifest where the code package is defined</span></span></param>
        <param name="codePackageName"><span data-ttu-id="355e7-619">Der Name des Pakets Code neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-619">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="355e7-620">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-620">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-621">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-621">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-622">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-622">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-623">Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-623">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-624">RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-624">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="355e7-625">SelectedReplica ist keine in dieser Überladung.</span><span class="sxs-lookup"><span data-stu-id="355e7-625">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-626">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-626">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-627">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-627">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-628">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-628">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-629">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</span><span class="sxs-lookup"><span data-stu-id="355e7-629">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-630">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-630">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-631">Der Knoten, auf dem das Codepaket gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-631">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="355e7-632">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-632">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="355e7-633">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-633">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="355e7-634">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> von bereitgestelltes Dienstpaket, die das Codepaket enthält.</span><span class="sxs-lookup"><span data-stu-id="355e7-634">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package which contains the code package.</span></span> <span data-ttu-id="355e7-635">Sie erhalten die ServicePackageActivationId eines bereitgestellten Dienstpakets mit <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="355e7-635">You can get the ServicePackageActivationId of a deployed service package by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="355e7-636">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="355e7-636">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="355e7-637">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-637">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <param name="codePackageName"><span data-ttu-id="355e7-638">Der Name des Pakets Code neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-638">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="355e7-639">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-639">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-640">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-640">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-641">Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-641">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-642">RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-642">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="355e7-643">SelectedReplica ist keine in dieser Überladung.</span><span class="sxs-lookup"><span data-stu-id="355e7-643">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-644">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-644">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-645">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-645">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-646">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-646">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-647">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</span><span class="sxs-lookup"><span data-stu-id="355e7-647">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-648">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-648">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-649">Der Knoten, auf dem das Codepaket gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-649">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="355e7-650">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-650">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="355e7-651">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-651">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="codePackageName"><span data-ttu-id="355e7-652">Der Name des Pakets Code neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-652">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="355e7-653">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-653">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-654">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-654">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-655">Das gesamttimeout für den Vorgang, z. B. das Timeout warten Codepaket wenn Neustart <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</span><span class="sxs-lookup"><span data-stu-id="355e7-655">The overall timeout for the operation including the timeout to wait for code package to restart if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="355e7-656">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-656">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-657">Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-657">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-658">RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-658">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="355e7-659">SelectedReplica ist keine in dieser Überladung.</span><span class="sxs-lookup"><span data-stu-id="355e7-659">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-660">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-660">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-661">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-661">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-662">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-662">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-663">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</span><span class="sxs-lookup"><span data-stu-id="355e7-663">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-664">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-664">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-665">Der Knoten, auf dem das Codepaket gehostet wird</span><span class="sxs-lookup"><span data-stu-id="355e7-665">The node on which the code package is hosted</span></span></param>
        <param name="applicationName"><span data-ttu-id="355e7-666">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-666">The name of the application to which the code package belongs</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="355e7-667">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist</span><span class="sxs-lookup"><span data-stu-id="355e7-667">The name of the service manifest where the code package is defined</span></span></param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="355e7-668">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> von bereitgestelltes Dienstpaket, die das Codepaket enthält.</span><span class="sxs-lookup"><span data-stu-id="355e7-668">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package which contains the code package.</span></span> <span data-ttu-id="355e7-669">Sie erhalten die ServicePackageActivationId eines bereitgestellten Dienstpakets mit <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="355e7-669">You can get the ServicePackageActivationId of a deployed service package by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="355e7-670">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="355e7-670">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="355e7-671">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-671">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <param name="codePackageName"><span data-ttu-id="355e7-672">Der Name des Pakets Code neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-672">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="355e7-673">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-673">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-674">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-674">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-675">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-675">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-676">Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-676">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-677">RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-677">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="355e7-678">SelectedReplica ist keine in dieser Überladung.</span><span class="sxs-lookup"><span data-stu-id="355e7-678">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-679">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-679">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-680">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-680">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-681">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-681">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-682">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</span><span class="sxs-lookup"><span data-stu-id="355e7-682">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-683">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-683">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-684">Der Knoten, auf dem das Codepaket gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-684">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="355e7-685">Der Name der Anwendung, die das Codepaket angehört.</span><span class="sxs-lookup"><span data-stu-id="355e7-685">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="355e7-686">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-686">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="355e7-687">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> von bereitgestelltes Dienstpaket, die das Codepaket enthält.</span><span class="sxs-lookup"><span data-stu-id="355e7-687">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package which contains the code package.</span></span> <span data-ttu-id="355e7-688">Sie erhalten die ServicePackageActivationId eines bereitgestellten Dienstpakets mit <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="355e7-688">You can get the ServicePackageActivationId of a deployed service package by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="355e7-689">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="355e7-689">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="355e7-690">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-690">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <param name="codePackageName"><span data-ttu-id="355e7-691">Der Name des Pakets Code neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-691">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="355e7-692">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</span><span class="sxs-lookup"><span data-stu-id="355e7-692">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-693">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-693">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-694">Das gesamttimeout für den Vorgang, z. B. das Timeout warten Codepaket wenn Neustart <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</span><span class="sxs-lookup"><span data-stu-id="355e7-694">The overall timeout for the operation including the timeout to wait for code package to restart if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="355e7-695">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-695">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-696">Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-696">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-697">RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-697">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="355e7-698">SelectedReplica ist keine in dieser Überladung.</span><span class="sxs-lookup"><span data-stu-id="355e7-698">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-699">Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.</span><span class="sxs-lookup"><span data-stu-id="355e7-699">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-700">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-700">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-701">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-701">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-702">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</span><span class="sxs-lookup"><span data-stu-id="355e7-702">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="355e7-703">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</span><span class="sxs-lookup"><span data-stu-id="355e7-703">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-704">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="355e7-704">This parameter is used to choose a specific replica.</span></span>  <span data-ttu-id="355e7-705">Dieses Replikat entsprechenden Knoten werden neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-705">This replica's corresponding node will be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-706">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.</span><span class="sxs-lookup"><span data-stu-id="355e7-706">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="355e7-707">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-707">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-708">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-708">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-709">Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-709">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-710">Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-710">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-711">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-711">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="355e7-712">Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-712">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="355e7-713">Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="355e7-713">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="355e7-714">Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="355e7-714">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-715">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-715">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-716">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-716">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-717">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="355e7-717">This parameter is used to choose a specific replica.</span></span>  <span data-ttu-id="355e7-718">Dieses Replikat entsprechenden Knoten werden neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-718">This replica's corresponding node will be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-719">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.</span><span class="sxs-lookup"><span data-stu-id="355e7-719">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="355e7-720">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-720">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-721">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-721">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-722">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-722">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-723">Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-723">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-724">Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-724">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-725">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-725">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="355e7-726">Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-726">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="355e7-727">Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="355e7-727">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="355e7-728">Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="355e7-728">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-729">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-729">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-730">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-730">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-731">Der Knotenname des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-731">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="355e7-732">Die Knoten-ID des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-732">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="355e7-733">Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-733">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="355e7-734">Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-734">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="355e7-735">Wenn die Instanz einen positiven Wert aufweist, wird er mit dem aktiven Knoten-ID verglichen.</span><span class="sxs-lookup"><span data-stu-id="355e7-735">If the instance has a positive value, it is compared with the active node ID.</span></span>
            <span data-ttu-id="355e7-736">Wenn die IDs nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="355e7-736">If the IDs do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="355e7-737">Dieser Fehler kann durch eine veraltete Nachricht verursacht.</span><span class="sxs-lookup"><span data-stu-id="355e7-737">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="completionMode"><span data-ttu-id="355e7-738">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.</span><span class="sxs-lookup"><span data-stu-id="355e7-738">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="355e7-739">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-739">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-740">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-740">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-741">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-741">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-742">Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-742">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-743">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-743">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="355e7-744">Wenn der Fehlercode NodeNotFound NodeName lautet oder NodeInstance ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-744">If the ErrorCode is NodeNotFound, nodeName or nodeInstance is invalid.</span></span>
              <span data-ttu-id="355e7-745">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.</span><span class="sxs-lookup"><span data-stu-id="355e7-745">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-746">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-746">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-747">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-747">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-748">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="355e7-748">This parameter is used to choose a specific replica.</span></span>
            <span data-ttu-id="355e7-749">Der Knoten, auf dem das Replikat bereitgestellt wird, wird neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-749">The node where the replica is deployed will be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-750">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.</span><span class="sxs-lookup"><span data-stu-id="355e7-750">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="355e7-751">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-751">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-752">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-752">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-753">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-753">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-754">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-754">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-755">Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-755">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-756">Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-756">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-757">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-757">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="355e7-758">Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-758">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="355e7-759">Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="355e7-759">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="355e7-760">Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="355e7-760">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-761">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-761">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-762">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-762">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-763">Der Knotenname des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-763">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="355e7-764">Die Knoten-ID des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-764">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="355e7-765">Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-765">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="355e7-766">Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-766">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="355e7-767">Wenn die Instanz einen positiven Wert aufweist, wird er mit der aktiven Instanz-ID verglichen.</span><span class="sxs-lookup"><span data-stu-id="355e7-767">If the instance has a positive value, it is compared with the active instance ID.</span></span>
            <span data-ttu-id="355e7-768">Wenn die Instanzen nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="355e7-768">If the instances do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="355e7-769">Dieser Fehler kann durch eine veraltete Nachricht verursacht.</span><span class="sxs-lookup"><span data-stu-id="355e7-769">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="completionMode"><span data-ttu-id="355e7-770">Wenn auf festgelegt <see cref="F:System.Fabric.CompletionMode.Verify" />, das System überprüft, dass der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.</span><span class="sxs-lookup"><span data-stu-id="355e7-770">If set to <see cref="F:System.Fabric.CompletionMode.Verify" />, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>
            <span data-ttu-id="355e7-771">Wenn auf festgelegt <see cref="F:System.Fabric.CompletionMode.DoNotVerify" />, die API gibt zurück, nachdem der Knoten Neustart initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-771">If set to <see cref="F:System.Fabric.CompletionMode.DoNotVerify" />, the API returns once the node restart has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-772">Das CancellationToken, das diesen Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-772">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="355e7-773">Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="355e7-773">It is used to notify the operation that it should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-774">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-774">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-775">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-775">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-776">Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-776">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-777">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-777">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  <span data-ttu-id="355e7-778">Wenn ErrorCode NodeNotFound ist, ist der "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-778">If the ErrorCode is NodeNotFound, nodeName is invalid.</span></span>
            <span data-ttu-id="355e7-779">Wenn ErrorCode InstanceIdMismatch, ist die <paramref name="nodeInstance" /> bereitgestellten die gerade ausgeführte Instanz stimmt nicht überein.</span><span class="sxs-lookup"><span data-stu-id="355e7-779">If the ErrorCode is InstanceIdMismatch, the <paramref name="nodeInstance" /> provided does not match the currently running instance.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-780">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-780">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-781">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-781">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestartNodeAsync (nodeName As String, nodeInstance As BigInteger, operationTimeout As TimeSpan, token As CancellationToken) As Task(Of RestartNodeResult)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-782">Der Knotenname des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-782">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="355e7-783">Die Knoten-ID des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-783">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="355e7-784">Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-784">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="355e7-785">Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-785">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="355e7-786">Wenn die Instanz einen positiven Wert aufweist, wird er mit dem aktiven Knoten-ID verglichen.</span><span class="sxs-lookup"><span data-stu-id="355e7-786">If the instance has a positive value, it is compared with the active node ID.</span></span>
            <span data-ttu-id="355e7-787">Wenn die IDs nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="355e7-787">If the IDs do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="355e7-788">Dieser Fehler kann durch eine veraltete Nachricht verursacht.</span><span class="sxs-lookup"><span data-stu-id="355e7-788">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="operationTimeout"><span data-ttu-id="355e7-789">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-789">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-790">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-790">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-791">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-791">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-792">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-792">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-793">Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-793">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-794">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-794">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-795">Wenn ErrorCode NodeNotFound ist, ist der "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-795">If the ErrorCode is NodeNotFound, nodeName is invalid.</span></span>  
              <span data-ttu-id="355e7-796">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.</span><span class="sxs-lookup"><span data-stu-id="355e7-796">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-797">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-797">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-798">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-798">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-799">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="355e7-799">This parameter is used to choose a specific replica.</span></span>  <span data-ttu-id="355e7-800">Dieses Replikat entsprechenden Knoten werden neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-800">This replica's corresponding node will be restarted.</span></span></param>
        <param name="createFabricDump"> <span data-ttu-id="355e7-801">Wenn auf True festgelegt, das System das Speicherabbild des Prozesses für Fabric.exe auf diesem Knoten erstellen.</span><span class="sxs-lookup"><span data-stu-id="355e7-801">If set to true, the system will create the process dump for Fabric.exe on this node.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-802">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.</span><span class="sxs-lookup"><span data-stu-id="355e7-802">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="355e7-803">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-803">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-804">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-804">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-805">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-805">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-806">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-806">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-807">Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-807">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks><span data-ttu-id="355e7-808">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-808">A cluster node is a process, not an virtual or physical machine.</span></span>
            <span data-ttu-id="355e7-809">Wenn der CreateFabricDump-Parameter festgelegt ist, beim Neustart des Prozesses abgestürzt ist, und das Absturzabbild befindet sich im Ordner Absturzabbilder, die die DCA hochladen konfiguriert werden können.</span><span class="sxs-lookup"><span data-stu-id="355e7-809">If the createFabricDump parameter is set, on restart the process is crashed and the crash dump is placed in the Crash Dumps folder which the DCA can be configured to upload.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-810">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-810">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="355e7-811">Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-811">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="355e7-812">Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="355e7-812">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="355e7-813">Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="355e7-813">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-814">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-814">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-815">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-815">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-816">Der Knotenname des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-816">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="355e7-817">Die Knoten-ID des Knotens, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-817">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="355e7-818">Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-818">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="355e7-819">Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-819">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="355e7-820">Wenn die Instanz einen positiven Wert aufweist, wird er mit dem aktiven Knoten-ID verglichen.</span><span class="sxs-lookup"><span data-stu-id="355e7-820">If the instance has a positive value, it is compared with the active node ID.</span></span>
            <span data-ttu-id="355e7-821">Wenn die IDs nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="355e7-821">If the IDs do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="355e7-822">Dieser Fehler kann durch eine veraltete Nachricht verursacht.</span><span class="sxs-lookup"><span data-stu-id="355e7-822">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="createFabricDump"> <span data-ttu-id="355e7-823">Wenn auf True festgelegt, das System das Speicherabbild des Prozesses für Fabric.exe auf diesem Knoten erstellen.</span><span class="sxs-lookup"><span data-stu-id="355e7-823">If set to true, the system will create the process dump for Fabric.exe on this node.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-824">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.</span><span class="sxs-lookup"><span data-stu-id="355e7-824">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="355e7-825">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-825">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-826">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-826">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-827">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-827">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-828">Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.</span><span class="sxs-lookup"><span data-stu-id="355e7-828">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-829">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-829">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="355e7-830">Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-830">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-831">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-831">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-832">Wenn ErrorCode NodeNotFound ist, ist der "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-832">If the ErrorCode is NodeNotFound, nodeName is invalid.</span></span>  
              <span data-ttu-id="355e7-833">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.</span><span class="sxs-lookup"><span data-stu-id="355e7-833">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-834">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-834">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-835">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-835">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-836">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-836">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be restarted.</span></span> <span data-ttu-id="355e7-837">Diese API kann nur für persistente dienstreplikate aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-837">This API can only be called for persisted service replicas.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-838">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-838">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <summary>
            <span data-ttu-id="355e7-839">Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-839">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-840">Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-840">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-841">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-841">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-842">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-842">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-843">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-843">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-844">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-844">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be restarted.</span></span> <span data-ttu-id="355e7-845">Diese API kann nur für persistente dienstreplikate aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-845">This API can only be called for persisted service replicas.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-846">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-846">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="token"><span data-ttu-id="355e7-847">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-847">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-848">Diese API wird das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen ReplicaSelector neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-848">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in ReplicaSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-849">Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-849">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-850">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-850">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-851">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-851">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-852">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-852">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="355e7-853">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-853">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be restarted.</span></span> <span data-ttu-id="355e7-854">Diese API kann nur für persistente dienstreplikate aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-854">This API can only be called for persisted service replicas.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-855">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-855">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-856">Das gesamttimeout für den Vorgang, der das Timeout warten, bis Replikat neu gestartet werden, einschließlich <see cref="T:System.Fabric.CompletionMode" /> stellen Sie sicher ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-856">The overall timeout for the operation including the timeout to wait for replica to be restarted if <see cref="T:System.Fabric.CompletionMode" /> is Verify.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-857">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-857">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-858">Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-858">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-859">Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-859">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-860">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-860">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-861">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-861">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-862">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="355e7-862">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-863">Name des Knotens, auf dem Replikat muss neu gestartet werden<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="355e7-863">Node name where replica needs to be restarted <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="355e7-864">Partitions-Id, in dem das Replikat muss neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-864">Partition Id where the replica needs to be restarted</span></span> </param>
        <param name="replicaId"><span data-ttu-id="355e7-865">Replikat-Id, die neu gestartet werden muss</span><span class="sxs-lookup"><span data-stu-id="355e7-865">Replica Id that needs to be restarted</span></span> </param>
        <param name="completionMode"><span data-ttu-id="355e7-866">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-866">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <summary>
            <span data-ttu-id="355e7-867">Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-867">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-868">Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-868">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-869">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-869">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-870">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-870">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-871">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-871">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-872">Name des Knotens, auf dem Replikat muss neu gestartet werden<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="355e7-872">Node name where replica needs to be restarted <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="355e7-873">Partitions-Id, in dem das Replikat muss neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-873">Partition Id where the replica needs to be restarted</span></span> </param>
        <param name="replicaId"><span data-ttu-id="355e7-874">Replikat-Id, die neu gestartet werden muss</span><span class="sxs-lookup"><span data-stu-id="355e7-874">Replica Id that needs to be restarted</span></span> </param>
        <param name="completionMode"><span data-ttu-id="355e7-875">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-875">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="token"><span data-ttu-id="355e7-876">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-876">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-877">Diese API wird das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen ReplicaSelector neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="355e7-877">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in ReplicaSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-878">Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-878">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-879">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-879">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-880">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-880">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-881">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-881">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-882">Name des Knotens, auf dem Replikat muss neu gestartet werden<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="355e7-882">Node name where replica needs to be restarted <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="355e7-883">Partitions-Id, in dem das Replikat muss neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="355e7-883">Partition Id where the replica needs to be restarted</span></span> </param>
        <param name="replicaId"><span data-ttu-id="355e7-884">Replikat-Id, die neu gestartet werden muss</span><span class="sxs-lookup"><span data-stu-id="355e7-884">Replica Id that needs to be restarted</span></span> </param>
        <param name="completionMode"><span data-ttu-id="355e7-885">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</span><span class="sxs-lookup"><span data-stu-id="355e7-885">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="operationTimeoutSec"><span data-ttu-id="355e7-886">Das allgemeine Timeout in Sekunden für den Vorgang, der das Timeout warten, bis Replikat neu gestartet werden, einschließlich <see cref="T:System.Fabric.CompletionMode" /> stellen Sie sicher ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-886">The overall timeout in seconds for the operation, including the timeout to wait for replica to be restarted if <see cref="T:System.Fabric.CompletionMode" /> is Verify.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-887">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="355e7-887">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="355e7-888">Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.</span><span class="sxs-lookup"><span data-stu-id="355e7-888">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-889">Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</span><span class="sxs-lookup"><span data-stu-id="355e7-889">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-890">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="355e7-890">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-891">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="355e7-891">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-892">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="355e7-892">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-893">Der Knotenname des Knotens zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-893">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-894">Die Knoten-ID des Knotens, bevor er angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-894">The node instance ID of the node, before it was stopped.</span></span> <span data-ttu-id="355e7-895">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-895">If this is not specified, or is set to 0, this is ignored.</span></span> <span data-ttu-id="355e7-896">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-896">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-897">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-897">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-898">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-898">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-899">Startet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-899">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-900">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-900">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="355e7-901">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-901">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-902">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-902">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-903">Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-903">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="355e7-904">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-904">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="355e7-905">Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.</span><span class="sxs-lookup"><span data-stu-id="355e7-905">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-906">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-906">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-907">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-907">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-908">Der Knotenname des Knotens zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-908">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-909">Die Knoten-ID des Knotens, bevor er angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-909">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="355e7-910">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-910">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="355e7-911">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-911">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-912">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-912">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-913">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-913">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-914">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-914">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-915">Startet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-915">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-916">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-916">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="355e7-917">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-917">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-918">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-918">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-919">Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-919">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="355e7-920">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-920">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="355e7-921">Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.</span><span class="sxs-lookup"><span data-stu-id="355e7-921">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-922">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-922">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-923">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-923">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-924">Der Knotenname des Knotens zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-924">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-925">Die Knoten-ID des Knotens, bevor er angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-925">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="355e7-926">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-926">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="355e7-927">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-927">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="ipAddressOrFQDN"><span data-ttu-id="355e7-928">Die IP-Adresse oder den vollqualifizierten Domänennamen (FQDN des Zielknotens).</span><span class="sxs-lookup"><span data-stu-id="355e7-928">The IP address or fully-qualified domain name (FQDN) of the target node.</span></span>  <span data-ttu-id="355e7-929">Wenn dieser Parameter angegeben wird, "ClusterConnectionPort" muss auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-929">If this parameter is specified, 'ClusterConnectionPort" also must be specified.</span></span>  <span data-ttu-id="355e7-930">Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</span><span class="sxs-lookup"><span data-stu-id="355e7-930">If neither is specified, the system internally determines these.</span></span></param>
        <param name="clusterConnectionPort"><span data-ttu-id="355e7-931">Der Cluster Verbindungsport des Zielknotens.</span><span class="sxs-lookup"><span data-stu-id="355e7-931">The cluster connection port of the target node.</span></span>  <span data-ttu-id="355e7-932">Wenn dieser Parameter angegeben wird, muss auch "IpAddressOrFQDN" angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-932">If this parameter is specified, 'ipAddressOrFQDN' also must be specified.</span></span>  <span data-ttu-id="355e7-933">Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</span><span class="sxs-lookup"><span data-stu-id="355e7-933">If neither is specified, the system internally determines these.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-934">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-934">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-935">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-935">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-936">Startet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-936">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-937">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-937">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="355e7-938">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-938">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-939">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-939">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-940">Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-940">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="355e7-941">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-941">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="355e7-942">Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.</span><span class="sxs-lookup"><span data-stu-id="355e7-942">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-943">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-943">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-944">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-944">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-945">Der Knotenname des Knotens zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-945">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-946">Die Knoten-ID des Knotens, bevor er angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-946">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="355e7-947">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-947">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="355e7-948">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-948">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="ipAddressOrFQDN"><span data-ttu-id="355e7-949">Die IP-Adresse oder den vollqualifizierten Domänennamen (FQDN des Zielknotens).</span><span class="sxs-lookup"><span data-stu-id="355e7-949">The IP address or fully-qualified domain name (FQDN) of the target node.</span></span>  <span data-ttu-id="355e7-950">Wenn dieser Parameter angegeben wird, <paramref name="clusterConnectionPort" /> muss auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-950">If this parameter is specified, <paramref name="clusterConnectionPort" /> also must be specified.</span></span>  <span data-ttu-id="355e7-951">Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</span><span class="sxs-lookup"><span data-stu-id="355e7-951">If neither is specified, the system internally determines these.</span></span></param>
        <param name="clusterConnectionPort"><span data-ttu-id="355e7-952">Der Cluster Verbindungsport des Zielknotens.</span><span class="sxs-lookup"><span data-stu-id="355e7-952">The cluster connection port of the target node.</span></span>  <span data-ttu-id="355e7-953">Wenn dieser Parameter angegeben wird, <paramref name="ipAddressOrFQDN" /> muss auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-953">If this parameter is specified, <paramref name="ipAddressOrFQDN" /> also must be specified.</span></span>  <span data-ttu-id="355e7-954">Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</span><span class="sxs-lookup"><span data-stu-id="355e7-954">If neither is specified, the system internally determines these.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-955">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-955">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-956">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-956">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-957">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-957">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-958">Startet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-958">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-959">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-959">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="355e7-960">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-960">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-961">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-961">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-962">Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-962">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="355e7-963">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-963">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="355e7-964">Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.</span><span class="sxs-lookup"><span data-stu-id="355e7-964">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-965">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-965">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-966">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-966">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StartNodeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-967">Der Knotenname des Knotens zu starten.</span><span class="sxs-lookup"><span data-stu-id="355e7-967">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-968">Die Knoten-ID des Knotens, bevor er angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-968">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="355e7-969">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-969">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="355e7-970">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-970">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="ipAddressOrFQDN"><span data-ttu-id="355e7-971">Die IP-Adresse oder den vollqualifizierten Domänennamen (FQDN des Zielknotens).</span><span class="sxs-lookup"><span data-stu-id="355e7-971">The IP address or fully-qualified domain name (FQDN) of the target node.</span></span>  <span data-ttu-id="355e7-972">Wenn dieser Parameter angegeben wird, <paramref name="clusterConnectionPort" /> muss auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-972">If this parameter is specified, <paramref name="clusterConnectionPort" /> also must be specified.</span></span>  <span data-ttu-id="355e7-973">Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</span><span class="sxs-lookup"><span data-stu-id="355e7-973">If neither is specified, the system internally determines these.</span></span></param>
        <param name="clusterConnectionPort"><span data-ttu-id="355e7-974">Der Cluster Verbindungsport des Zielknotens.</span><span class="sxs-lookup"><span data-stu-id="355e7-974">The cluster connection port of the target node.</span></span>  <span data-ttu-id="355e7-975">Wenn dieser Parameter angegeben wird, <paramref name="ipAddressOrFQDN" /> muss auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="355e7-975">If this parameter is specified, <paramref name="ipAddressOrFQDN" /> also must be specified.</span></span>  <span data-ttu-id="355e7-976">Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</span><span class="sxs-lookup"><span data-stu-id="355e7-976">If neither is specified, the system internally determines these.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-977">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-977">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-978">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-978">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-979">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-979">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-980">Das cancellationToken</span><span class="sxs-lookup"><span data-stu-id="355e7-980">The cancellationToken</span></span></param>
        <summary>
            <span data-ttu-id="355e7-981">Startet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-981">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-982">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-982">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="355e7-983">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-983">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-984">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-984">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-985">Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="355e7-985">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="355e7-986">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-986">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="355e7-987">Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.</span><span class="sxs-lookup"><span data-stu-id="355e7-987">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-988">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-988">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-989">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-989">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-990">Der Knotenname des Knotens zu beenden.</span><span class="sxs-lookup"><span data-stu-id="355e7-990">The node name of the node to stop.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-991">Die Knoten-ID des Knotens zu beenden.</span><span class="sxs-lookup"><span data-stu-id="355e7-991">The node instance ID of the node to stop.</span></span>  <span data-ttu-id="355e7-992">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-992">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="355e7-993">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-993">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-994">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten beendet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-994">If set to Verify, the system will check that the node stopped, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-995">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten beenden initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-995">If set to DoNotVerify, the API returns once the node stop has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-996">Beendet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-996">Stops a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-997">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-997">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="355e7-998">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-998">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-999">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-999">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-1000">Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-1000">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>  
              <span data-ttu-id="355e7-1001">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.</span><span class="sxs-lookup"><span data-stu-id="355e7-1001">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-1002">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-1002">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-1003">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-1003">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-1004">Der Knotenname des Knotens zu beenden.</span><span class="sxs-lookup"><span data-stu-id="355e7-1004">The node name of the node to stop.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-1005">Die Knoten-ID des Knotens zu beenden.</span><span class="sxs-lookup"><span data-stu-id="355e7-1005">The node instance ID of the node to stop.</span></span>  <span data-ttu-id="355e7-1006">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-1006">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="355e7-1007">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-1007">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-1008">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten beendet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-1008">If set to Verify, the system will check that the node stopped, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-1009">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten beenden initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-1009">If set to DoNotVerify, the API returns once the node stop has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-1010">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-1010">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-1011">Beendet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-1011">Stops a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-1012">Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-1012">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="355e7-1013">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-1013">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-1014">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-1014">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-1015">Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-1015">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>  
              <span data-ttu-id="355e7-1016">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.</span><span class="sxs-lookup"><span data-stu-id="355e7-1016">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-1017">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-1017">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-1018">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-1018">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StopNodeAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="355e7-1019">Der Knotenname des Knotens zu beenden.</span><span class="sxs-lookup"><span data-stu-id="355e7-1019">The node name of the node to stop.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="355e7-1020">Die Knoten-ID des Knotens zu beenden.</span><span class="sxs-lookup"><span data-stu-id="355e7-1020">The node instance ID of the node to stop.</span></span>  <span data-ttu-id="355e7-1021">Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.</span><span class="sxs-lookup"><span data-stu-id="355e7-1021">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="355e7-1022">Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</span><span class="sxs-lookup"><span data-stu-id="355e7-1022">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="355e7-1023">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten beendet, und die API gibt nicht zurück, bis sie verfügt.</span><span class="sxs-lookup"><span data-stu-id="355e7-1023">If set to Verify, the system will check that the node stopped, and the API will not return until it has.</span></span>  <span data-ttu-id="355e7-1024">Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten beenden initiiert wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-1024">If set to DoNotVerify, the API returns once the node stop has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="355e7-1025">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="355e7-1025">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="355e7-1026">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="355e7-1026">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="355e7-1027">Beendet einen Clusterknoten an.</span><span class="sxs-lookup"><span data-stu-id="355e7-1027">Stops a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="355e7-1028">Ein Task mit Informationen, die den Zielknoten darstellt.</span><span class="sxs-lookup"><span data-stu-id="355e7-1028">A task with information representing the target node</span></span></returns>
        <remarks><span data-ttu-id="355e7-1029">Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</span><span class="sxs-lookup"><span data-stu-id="355e7-1029">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="355e7-1030">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="355e7-1030">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="355e7-1031">Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.</span><span class="sxs-lookup"><span data-stu-id="355e7-1031">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>  
              <span data-ttu-id="355e7-1032">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.</span><span class="sxs-lookup"><span data-stu-id="355e7-1032">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="355e7-1033">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="355e7-1033">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="355e7-1034">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="355e7-1034">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>