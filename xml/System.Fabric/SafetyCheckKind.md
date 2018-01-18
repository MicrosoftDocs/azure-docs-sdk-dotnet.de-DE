<Type Name="SafetyCheckKind" FullName="System.Fabric.SafetyCheckKind">
  <TypeSignature Language="C#" Value="public enum SafetyCheckKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SafetyCheckKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SafetyCheckKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum SafetyCheckKind" />
  <TypeSignature Language="F#" Value="type SafetyCheckKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="8779c-101">Eine Service Fabric-Enumeration, die die upgradesicherheitsüberprüfung angibt ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="8779c-101">A Service Fabric enumeration that indicates the upgrade safety check performed.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnsureAvailability">
      <MemberSignature Language="C#" Value="EnsureAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind EnsureAvailability = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.EnsureAvailability" />
      <MemberSignature Language="VB.NET" Value="EnsureAvailability" />
      <MemberSignature Language="F#" Value="EnsureAvailability = 7" Usage="System.Fabric.SafetyCheckKind.EnsureAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-102">Gibt an, entweder eine zustandslose Dienstpartition auf den Knoten mit genau einer Instanz vorhanden ist, oder dass ein primäres Replikat auf dem Knoten für den Partition einen quorumsverlust darstellt.</span><span class="sxs-lookup"><span data-stu-id="8779c-102">Indicates that there is either a stateless service partition on the node having exactly one instance, or there is a primary replica on the node for which the partition is quorum loss.</span></span> <span data-ttu-id="8779c-103">In beiden Fällen wird führt das Replikat heruntergefahren nichtverfügbarkeit.</span><span class="sxs-lookup"><span data-stu-id="8779c-103">In both cases, bringing down the replica will result in loss of availability.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsurePartitionQuorum">
      <MemberSignature Language="C#" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind EnsurePartitionQuorum = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.EnsurePartitionQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="F#" Value="EnsurePartitionQuorum = 2" Usage="System.Fabric.SafetyCheckKind.EnsurePartitionQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-104">Gibt an, dass eine Partition für die Wenn wir das Replikat auf dem Knoten beenden quorumsverlust für diese Partition dadurch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="8779c-104">Indicates that there is some partition for which if we bring down the replica on the node, it will result in quorum loss for that partition.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsureSeedNodeQuorum">
      <MemberSignature Language="C#" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind EnsureSeedNodeQuorum = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="F#" Value="EnsureSeedNodeQuorum = 1" Usage="System.Fabric.SafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-105">Gibt an, dass wenn wir den Knoten Beenden klicken Sie dann diese im globalen Seed-Knoten quorumsverlust führt.</span><span class="sxs-lookup"><span data-stu-id="8779c-105">Indicates that if we bring down the node then this will result in global seed node quorum loss.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.SafetyCheckKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-106">Gibt an, dass die Art der upgradesicherheitsüberprüfung ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="8779c-106">Indicates that the upgrade safety check kind is invalid.</span></span> <span data-ttu-id="8779c-107">Dieser Wert wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="8779c-107">This value is not used.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForInBuildReplica">
      <MemberSignature Language="C#" Value="WaitForInBuildReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForInBuildReplica = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForInBuildReplica" />
      <MemberSignature Language="VB.NET" Value="WaitForInBuildReplica" />
      <MemberSignature Language="F#" Value="WaitForInBuildReplica = 6" Usage="System.Fabric.SafetyCheckKind.WaitForInBuildReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-108">Gibt an, auf den Knoten, der über Kopiervorgang relevant ist entweder ein Replikat vorhanden ist, oder dass ein primäres Replikat auf dem Knoten, der Daten auf ein anderes Replikat kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="8779c-108">Indicates that there is either a replica on the node that is going through copy, or there is a primary replica on the node that is copying data to some other replica.</span></span> <span data-ttu-id="8779c-109">In beiden Fällen wird das Replikat auf dem Knoten heruntergefahren der Kopiervorgang abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="8779c-109">In both cases, bringing down the replica on the node will abort the copy.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimaryPlacement">
      <MemberSignature Language="C#" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForPrimaryPlacement = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="F#" Value="WaitForPrimaryPlacement = 3" Usage="System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-110">Gibt an, dass ein Replikat auf dem Knoten, der von diesem Knoten verschoben wurde.</span><span class="sxs-lookup"><span data-stu-id="8779c-110">Indicates that there is some replica on the node that was moved out of this node.</span></span> <span data-ttu-id="8779c-111">Service Fabric wartet jetzt für den primären wieder auf diesen Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="8779c-111">Service Fabric is now waiting for the primary to be moved back to this node.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimarySwap">
      <MemberSignature Language="C#" Value="WaitForPrimarySwap" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForPrimarySwap = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForPrimarySwap" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimarySwap" />
      <MemberSignature Language="F#" Value="WaitForPrimarySwap = 4" Usage="System.Fabric.SafetyCheckKind.WaitForPrimarySwap" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-112">Gibt an, dass Service Fabric wartet ein primäres Replikat aus dem Knoten verschoben werden soll.</span><span class="sxs-lookup"><span data-stu-id="8779c-112">Indicates that Service Fabric is waiting for a primary replica to be moved out of the node.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForReconfiguration">
      <MemberSignature Language="C#" Value="WaitForReconfiguration" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForReconfiguration = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForReconfiguration" />
      <MemberSignature Language="VB.NET" Value="WaitForReconfiguration" />
      <MemberSignature Language="F#" Value="WaitForReconfiguration = 5" Usage="System.Fabric.SafetyCheckKind.WaitForReconfiguration" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="8779c-113">Gibt an, dass es ein Replikat auf dem Knoten, der an einer Neukonfiguration beteiligt ist und Fabric-Dienst wartet darauf, dass die Neukonfiguration abgeschlossen sein muss.</span><span class="sxs-lookup"><span data-stu-id="8779c-113">Indicates that there is some replica on the node that is involved in a reconfiguration and Service Fabric is waiting for the reconfiguration to be complete.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>