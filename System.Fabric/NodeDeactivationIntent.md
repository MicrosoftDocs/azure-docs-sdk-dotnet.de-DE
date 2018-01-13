<Type Name="NodeDeactivationIntent" FullName="System.Fabric.NodeDeactivationIntent">
  <TypeSignature Language="C#" Value="public enum NodeDeactivationIntent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeDeactivationIntent extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeDeactivationIntent" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeDeactivationIntent" />
  <TypeSignature Language="F#" Value="type NodeDeactivationIntent = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="d5883-101">Beschreibt den Grund, warum der Knoten deaktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="d5883-101">Describes the reason why the node is being deactivated.</span></span></para>
    </summary>
    <remarks>
      <para>
                <span data-ttu-id="d5883-102">Die <see cref="T:System.Fabric.NodeDeactivationIntent" /> Enumeration dient als Teil der <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="d5883-102">The <see cref="T:System.Fabric.NodeDeactivationIntent" /> enumeration is provided as a part of the <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" /> method.</span></span> </para>
      <para>
                <span data-ttu-id="d5883-103">Service Fabric verwendet diese Informationen, die richtigen Aktionen an den Knoten, um ein ordnungsgemäßes Herunterfahren des Knotens bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="d5883-103">Service Fabric uses this information to take the correct actions at the node to provide a graceful shutdown of the node.</span></span> <span data-ttu-id="d5883-104">Die Absichten weisen eine allgemeine Progression bzw. Schweregrade.</span><span class="sxs-lookup"><span data-stu-id="d5883-104">The intents have a general progression or severity.</span></span> </para>
      <para>
                <span data-ttu-id="d5883-105">Eine Deaktivierung, die mit einer Absicht gestartet wird, kann auf nachfolgende höhere Ebenen des Absicht erhöht werden.</span><span class="sxs-lookup"><span data-stu-id="d5883-105">A deactivation that is started with one intent can be increased to subsequent higher levels of intent.</span></span> <span data-ttu-id="d5883-106">Die allgemeine Abfolge dieser Progression ist: anhalten, neu starten, beenden, "forcestop".</span><span class="sxs-lookup"><span data-stu-id="d5883-106">The general order of this progression is: Pause, Restart, Stop, ForceStop.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d5883-107">Gibt an, dass eine Datei deaktivierungsabsicht ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="d5883-107">Indicates that a deactivation intent is invalid.</span></span> <span data-ttu-id="d5883-108">Dieser Wert wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="d5883-108">This value is not used.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Pause">
      <MemberSignature Language="C#" Value="Pause" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Pause = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberSignature Language="VB.NET" Value="Pause" />
      <MemberSignature Language="F#" Value="Pause = 1" Usage="System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d5883-109">Gibt an, dass der Knoten angehalten werden soll.</span><span class="sxs-lookup"><span data-stu-id="d5883-109">Indicates that the node should be paused.</span></span> </para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="d5883-110">Wenn diese Absicht verwendet wird, wird verhindert, dass Service Fabric Änderungen an den angegebenen Knoten.</span><span class="sxs-lookup"><span data-stu-id="d5883-110">When this intent is used, Service Fabric prevents changes to the specified node.</span></span> <span data-ttu-id="d5883-111">Keine neuen Replikate auf dem Knoten platziert werden, und vorhandene Replikate nicht verschoben oder heruntergefahren werden.</span><span class="sxs-lookup"><span data-stu-id="d5883-111">No new replicas are placed on the node, and existing replicas are not moved or shut down.</span></span></para>
          <para>
                <span data-ttu-id="d5883-112">Die <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> Absicht ist nützlich, wenn eine oder mehrere Replikate auf einem Knoten Probleme auftreten, und dieser Knoten hat, zur weiteren Untersuchung isoliert werden müssen</span><span class="sxs-lookup"><span data-stu-id="d5883-112">The <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> intent is useful when one or more replicas on a node encounter issues and that node has to be isolated for further investigation</span></span></para>
          <para> 
                <span data-ttu-id="d5883-113">Diese Untersuchung kann den Zugriff auf den Remotecomputer zum Untersuchen von Aktivitäten wie das lokale-Protokolle und Speicherabbilder dauert beobachten von anderen Informationen enthalten.</span><span class="sxs-lookup"><span data-stu-id="d5883-113">This investigation could include accessing the remote machine to investigate such activities as reviewing local logs, taking memory dumps, and observing other information.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-114">Der Zweck dieser Modus wird versucht, den Knoten beibehält, sodass zusätzliche Debuggen unter denselben Umständen können, die vorhanden waren ausgeführt werden, als der Fehler auftrat.</span><span class="sxs-lookup"><span data-stu-id="d5883-114">The purpose of this mode is to attempt to preserve the node so that additional debugging can be performed under the same conditions that existed when the error occurred.</span></span></para>
          <para>
                <span data-ttu-id="d5883-115">Beachten Sie, dass die Angabe von diesem Modus nicht garantiert, dass alle Änderungen an den Knoten verhindert werden können.</span><span class="sxs-lookup"><span data-stu-id="d5883-115">Note that specifying this mode does not guarantee that all changes to the node can be prevented.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-116">Replikate auf dem Knoten stürzt möglicherweise ab, nachdem die Absicht, halten den Knoten empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="d5883-116">For example, replicas on the node might crash after the intent to pause the node has been received.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-117">Ein weiteres Beispiel möglicherweise Fehler in einem anderen Speicherort im Cluster ein sekundäres Replikat auf dem Knoten mit dem primären Replikat höher gestuft werden.</span><span class="sxs-lookup"><span data-stu-id="d5883-117">As another example, failures in another location in the cluster might cause a Secondary replica on the node to be promoted to the Primary replica.</span></span></para>
          <para>
                <span data-ttu-id="d5883-118">In diesem Modus wird Service Fabric Platzierung und Ausgleichen von Ressourcen auf dem Zielknoten deaktivieren</span><span class="sxs-lookup"><span data-stu-id="d5883-118">In this mode, Service Fabric will disable Placement and Resource Balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="d5883-119">Darüber hinaus Sicherheitsprüfungen (finden Sie unter <see cref="T:System.Fabric.SafetyCheckKind" />) ausgeführt wird. Service Fabric</span><span class="sxs-lookup"><span data-stu-id="d5883-119">In addition Safety Checks (see <see cref="T:System.Fabric.SafetyCheckKind" />) will be performed by Service Fabric</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveData">
      <MemberSignature Language="C#" Value="RemoveData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberSignature Language="VB.NET" Value="RemoveData" />
      <MemberSignature Language="F#" Value="RemoveData = 3" Usage="System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d5883-120">Gibt an, dass die Absicht des Knotens ein reimaging durchführen.</span><span class="sxs-lookup"><span data-stu-id="d5883-120">Indicates that the intent is to reimage the node.</span></span> <span data-ttu-id="d5883-121">Service Fabric ist den Knoten nicht erstellt: Diese Aktion erfolgt außerhalb von Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="d5883-121">Service Fabric does not reimage the node - this action is done outside of Service Fabric.</span></span></para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="d5883-122">Wenn Fabric-Dienst diese Absicht empfängt, es wird sichergestellt, die:</span><span class="sxs-lookup"><span data-stu-id="d5883-122">When Service Fabric receives this intent, it ensures that:</span></span> </para>
          <para>
                <span data-ttu-id="d5883-123">In diesem Modus verhindert, dass Service Fabric neue Replikate, die auf dem Knoten platziert wird.</span><span class="sxs-lookup"><span data-stu-id="d5883-123">In this mode, Service Fabric prevents new replicas from being placed on the node.</span></span> <span data-ttu-id="d5883-124">Service Fabric darüber hinaus werden folgende Aktionen ausgeführt:</span><span class="sxs-lookup"><span data-stu-id="d5883-124">Additionally, Service Fabric takes the following actions:</span></span> </para>
          <para>
                <span data-ttu-id="d5883-125">Deaktivieren der Platzierung und Ressourcenausgleich auf dem Zielknoten</span><span class="sxs-lookup"><span data-stu-id="d5883-125">Disable Placement and Resource balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="d5883-126">Verschieben Sie alle Sichern von Replikaten aus dem Knoten.</span><span class="sxs-lookup"><span data-stu-id="d5883-126">Move all Up replicas out of the node.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-127">Für Instanzen ohne Status impliziert dies erstellen eine andere Instanz auf einem anderen Knoten</span><span class="sxs-lookup"><span data-stu-id="d5883-127">For stateless instances this implies creating another instance on another node</span></span></para>
          <para>
                <span data-ttu-id="d5883-128">Für Replikate zustandsbehaftete Dienste ist ein Ersatz-Replikat auf einem anderen Knoten erstellt (wenn genügend Kapazität im Cluster)</span><span class="sxs-lookup"><span data-stu-id="d5883-128">For replicas of stateful services a replacement replica is built on another node (if there is sufficient capacity in the cluster)</span></span></para>
          <para>
                <span data-ttu-id="d5883-129">Wenn das Replikat ein primäres Replikat ist, ist das primäre vor dem Erstellen der Ersatz einige andere aktive sekundäre Kopie der Partition vorgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="d5883-129">If the replica is a primary, some other active secondary of the partition is made the primary prior to creating the replacement</span></span></para>
          <para>
                <span data-ttu-id="d5883-130">Zustandsbehaftete Replikate auf dem Knoten Benachrichtigungen senden, deren Zustand bereinigt und schließen.</span><span class="sxs-lookup"><span data-stu-id="d5883-130">Stateful replicas on the node receive notifications to clean up their state and close.</span></span></para>
          <para>
                <span data-ttu-id="d5883-131">Führt eine Teilmenge von sicherheitsüberprüfungen durch, die sicherstellen, dass als Ergebnis dauert dieser Knoten keine Daten verloren gehen können.</span><span class="sxs-lookup"><span data-stu-id="d5883-131">Performs a subset of safety checks that ensure that as a result of taking this node down no data loss can occur.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNode">
      <MemberSignature Language="C#" Value="RemoveNode" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveNode = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberSignature Language="VB.NET" Value="RemoveNode" />
      <MemberSignature Language="F#" Value="RemoveNode = 4" Usage="System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d5883-132">Gibt an, dass der Knoten außer Betrieb gesetzt werden wurde und wird nicht erwartet zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="d5883-132">Indicates that the node is being decommissioned and is not expected to return.</span></span> <span data-ttu-id="d5883-133">Service Fabric ist außer Betrieb, die Knoten - dadurch erfolgt außerhalb von Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="d5883-133">Service Fabric does not decommission the node - this action is done outside of Service Fabric.</span></span></para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="d5883-134">Wenn Fabric-Dienst diese Absicht empfängt, es wird sichergestellt, die:</span><span class="sxs-lookup"><span data-stu-id="d5883-134">When Service Fabric receives this intent, it ensures that:</span></span> </para>
          <para>
                <span data-ttu-id="d5883-135">In diesem Modus verhindert, dass Service Fabric neue Replikate, die auf dem Knoten platziert wird.</span><span class="sxs-lookup"><span data-stu-id="d5883-135">In this mode, Service Fabric prevents new replicas from being placed on the node.</span></span> <span data-ttu-id="d5883-136">Service Fabric darüber hinaus werden folgende Aktionen ausgeführt:</span><span class="sxs-lookup"><span data-stu-id="d5883-136">Additionally, Service Fabric takes the following actions:</span></span> </para>
          <para>
                <span data-ttu-id="d5883-137">Deaktivieren der Platzierung und Ressourcenausgleich auf dem Zielknoten</span><span class="sxs-lookup"><span data-stu-id="d5883-137">Disable Placement and Resource balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="d5883-138">Verschieben Sie alle Sichern von Replikaten aus dem Knoten.</span><span class="sxs-lookup"><span data-stu-id="d5883-138">Move all Up replicas out of the node.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-139">Für Instanzen ohne Status impliziert dies erstellen eine andere Instanz auf einem anderen Knoten</span><span class="sxs-lookup"><span data-stu-id="d5883-139">For stateless instances this implies creating another instance on another node</span></span></para>
          <para>
                <span data-ttu-id="d5883-140">Für Replikate zustandsbehaftete Dienste ist ein Ersatz-Replikat auf einem anderen Knoten erstellt (wenn genügend Kapazität im Cluster)</span><span class="sxs-lookup"><span data-stu-id="d5883-140">For replicas of stateful services a replacement replica is built on another node (if there is sufficient capacity in the cluster)</span></span></para>
          <para>
                <span data-ttu-id="d5883-141">Wenn das Replikat ein primäres Replikat ist, ist das primäre vor dem Erstellen der Ersatz einige andere aktive sekundäre Kopie der Partition vorgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="d5883-141">If the replica is a primary, some other active secondary of the partition is made the primary prior to creating the replacement</span></span></para>
          <para>
                <span data-ttu-id="d5883-142">Zustandsbehaftete Replikate auf dem Knoten Benachrichtigungen senden, deren Zustand bereinigt und schließen.</span><span class="sxs-lookup"><span data-stu-id="d5883-142">Stateful replicas on the node receive notifications to clean up their state and close.</span></span></para>
          <para>
                <span data-ttu-id="d5883-143">Führt eine Teilmenge von sicherheitsüberprüfungen durch, die sicherstellen, dass als Ergebnis dauert dieser Knoten keine Daten verloren gehen können.</span><span class="sxs-lookup"><span data-stu-id="d5883-143">Performs a subset of safety checks that ensure that as a result of taking this node down no data loss can occur.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="Restart" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Restart = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberSignature Language="VB.NET" Value="Restart" />
      <MemberSignature Language="F#" Value="Restart = 2" Usage="System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d5883-144">Gibt an, dass die Absicht für den Knoten nach kurzer Zeit neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="d5883-144">Indicates that the intent is for the node to be restarted after a short period of time.</span></span> <span data-ttu-id="d5883-145">Service Fabric nicht den Knoten neu gestartet: Diese Aktion erfolgt außerhalb von Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="d5883-145">Service Fabric does not restart the node - this action is done outside of Service Fabric.</span></span></para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="d5883-146">Ein Knoten kann z. B. beendet werden soll, führen Sie ein Betriebssystem oder einer Aktualisierung der Service Fabric-Code.</span><span class="sxs-lookup"><span data-stu-id="d5883-146">A node might be shut down, for example, to perform an OS update or a Service Fabric code update.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-147">In diesem Modus verhindert, dass Service Fabric neue Replikate, die auf dem Knoten platziert wird.</span><span class="sxs-lookup"><span data-stu-id="d5883-147">In this mode, Service Fabric prevents new replicas from being placed on the node.</span></span> <span data-ttu-id="d5883-148">Service Fabric darüber hinaus werden folgende Aktionen ausgeführt:</span><span class="sxs-lookup"><span data-stu-id="d5883-148">Additionally, Service Fabric takes the following actions:</span></span> </para>
          <para>
                <span data-ttu-id="d5883-149">Deaktivieren der Platzierung und Ressourcenausgleich auf dem Zielknoten</span><span class="sxs-lookup"><span data-stu-id="d5883-149">Disable Placement and Resource balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="d5883-150">Führt sicherheitsüberprüfungen durch.</span><span class="sxs-lookup"><span data-stu-id="d5883-150">Performs safety checks.</span></span> <span data-ttu-id="d5883-151">Die <see cref="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" /> sicherheitsüberprüfung für diese Absicht nicht ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="d5883-151">The <see cref="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" /> safety check is not performed for this intent.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-152">Schließen Sie alle Replikate und Instanzen, die auf den Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="d5883-152">Close all replicas and instances running on the node.</span></span></para>
          <para>
                <span data-ttu-id="d5883-153">Hinweis: Sobald von Replikaten und Instanzen schließen wird Service Fabric reaktiv Ersatz für Replikate zustandsbehaftete volatile Dienste und zustandslose Dienste erstellen.</span><span class="sxs-lookup"><span data-stu-id="d5883-153">NOTE: Once replicas and instances are closed, Service Fabric will reactively create replacements for replicas of stateful volatile services and stateless services.</span></span> </para>
          <para>
                <span data-ttu-id="d5883-154">Für Persisted Replikate auf dem Knoten, neue Replikate sind <b>nicht</b> erstellt werden, da die Absicht auf diesem Knoten neu zu starten und nach dem Neustart des persistenten Status wiederhergestellt ist.</span><span class="sxs-lookup"><span data-stu-id="d5883-154">For Persisted replicas on the node, new replicas are <b>not</b> be built, because the intention is to restart this node and to recover the persistent state after the restart.</span></span> <span data-ttu-id="d5883-155">Wenn der Knoten aktiviert ist, werden die Replikate geöffnet.</span><span class="sxs-lookup"><span data-stu-id="d5883-155">The replicas are opened once the node is activated.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>