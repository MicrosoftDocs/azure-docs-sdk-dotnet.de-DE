<Type Name="UpgradeSafetyCheckKind" FullName="System.Fabric.UpgradeSafetyCheckKind">
  <TypeSignature Language="C#" Value="public enum UpgradeSafetyCheckKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeSafetyCheckKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeSafetyCheckKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeSafetyCheckKind" />
  <TypeSignature Language="F#" Value="type UpgradeSafetyCheckKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="9ebc0-101">Listet die <see cref="T:System.Fabric.UpgradeSafetyCheck" /> , wird während des Upgrades für einen Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-101">Enumerates the <see cref="T:System.Fabric.UpgradeSafetyCheck" /> that is being performed for a node during upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnsureAvailability">
      <MemberSignature Language="C#" Value="EnsureAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsureAvailability = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsureAvailability" />
      <MemberSignature Language="VB.NET" Value="EnsureAvailability" />
      <MemberSignature Language="F#" Value="EnsureAvailability = 7" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsureAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-102">Gibt an, entweder eine zustandslose Dienstpartition auf den Knoten mit genau einer Instanz vorhanden ist, oder dass ein primäres Replikat auf dem Knoten für den Partition einen quorumsverlust darstellt.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-102">Indicates that there is either a stateless service partition on the node having exactly one instance, or there is a primary replica on the node for which the partition is quorum loss.</span></span> <span data-ttu-id="9ebc0-103">In beiden Fällen führt die Replikate aufgrund Upgrade heruntergefahren nichtverfügbarkeit.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-103">In both cases, bringing down the replicas due to upgrade will result in loss of availability.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsurePartitionQuorum">
      <MemberSignature Language="C#" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsurePartitionQuorum = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsurePartitionQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="F#" Value="EnsurePartitionQuorum = 2" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsurePartitionQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-104">Gibt an, dass eine Partition für die Wenn wir das Replikat auf dem Knoten beenden quorumsverlust für diese Partition dadurch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-104">Indicates that there is some partition for which if we bring down the replica on the node, it will result in quorum loss for that partition.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsureSeedNodeQuorum">
      <MemberSignature Language="C#" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsureSeedNodeQuorum = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="F#" Value="EnsureSeedNodeQuorum = 1" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-105">Gibt an, dass wenn wir den Knoten Beenden klicken Sie dann diese im globalen Seed-Knoten quorumsverlust führt.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-105">Indicates that if we bring down the node then this will result in global seed node quorum loss.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.UpgradeSafetyCheckKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-106">Gibt an, dass die Art der upgradesicherheitsüberprüfung ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-106">Indicates that the upgrade safety check kind is invalid.</span></span> <span data-ttu-id="9ebc0-107">Dieser Wert wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-107">This value is not used.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForInbuildReplica">
      <MemberSignature Language="C#" Value="WaitForInbuildReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForInbuildReplica = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForInbuildReplica" />
      <MemberSignature Language="VB.NET" Value="WaitForInbuildReplica" />
      <MemberSignature Language="F#" Value="WaitForInbuildReplica = 6" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForInbuildReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-108">Gibt an, auf den Knoten, der über Kopiervorgang relevant ist entweder ein Replikat vorhanden ist, oder dass ein primäres Replikat auf dem Knoten, der Daten auf ein anderes Replikat kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-108">Indicates that there is either a replica on the node that is going through copy, or there is a primary replica on the node that is copying data to some other replica.</span></span> <span data-ttu-id="9ebc0-109">In beiden Fällen wird das Replikat auf dem Knoten aufgrund heruntergefahren, aktualisiert der Kopiervorgang abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-109">In both cases, bringing down the replica on the node due to upgrade will abort the copy.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimaryPlacement">
      <MemberSignature Language="C#" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForPrimaryPlacement = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="F#" Value="WaitForPrimaryPlacement = 3" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-110">Gibt an, dass ein Replikat auf dem Knoten, der von diesem Knoten aufgrund verschoben wurde, zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-110">Indicates that there is some replica on the node that was moved out of this node due to upgrade.</span></span> <span data-ttu-id="9ebc0-111">Service Fabric wartet jetzt für den primären wieder auf diesen Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-111">Service Fabric is now waiting for the primary to be moved back to this node.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimarySwap">
      <MemberSignature Language="C#" Value="WaitForPrimarySwap" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForPrimarySwap = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForPrimarySwap" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimarySwap" />
      <MemberSignature Language="F#" Value="WaitForPrimarySwap = 4" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForPrimarySwap" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-112">Gibt an, dass Service Fabric wartet ein primäres Replikat vor dem Beginn der Aktualisierung auf diesem Knoten aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-112">Indicates that Service Fabric is waiting for a primary replica to be moved out of the node before starting upgrade on that node.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForReconfiguration">
      <MemberSignature Language="C#" Value="WaitForReconfiguration" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForReconfiguration = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForReconfiguration" />
      <MemberSignature Language="VB.NET" Value="WaitForReconfiguration" />
      <MemberSignature Language="F#" Value="WaitForReconfiguration = 5" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForReconfiguration" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-113">Gibt an, dass ein Replikat auf dem Knoten, der an einer Neukonfiguration beteiligt ist.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-113">Indicates that there is some replica on the node that is involved in a reconfiguration.</span></span> <span data-ttu-id="9ebc0-114">Service Fabric wartet darauf, dass eine Neukonfiguration vor dem Start abgeschlossen sein muss auf diesem Knoten Upgrades.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-114">Service Fabric is waiting for the reconfiguration to be complete before staring upgrade on that node.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForResourceAvailability">
      <MemberSignature Language="C#" Value="WaitForResourceAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForResourceAvailability = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForResourceAvailability" />
      <MemberSignature Language="VB.NET" Value="WaitForResourceAvailability" />
      <MemberSignature Language="F#" Value="WaitForResourceAvailability = 8" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForResourceAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9ebc0-115">Gibt an, dass immer noch nicht genügend Kapazität für die Ressource kontrolliert Metriken, um das Upgrade fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-115">Indicates that there is still not enough capacity for resource governed metrics to proceed with the upgrade.</span></span> <span data-ttu-id="9ebc0-116">Dies kann geschehen, für den Fall, dass Sie ein Dienstpaket Ressourcenverbrauch zunimmt.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-116">This can happen in case a service package is increasing resource consumption.</span></span> <span data-ttu-id="9ebc0-117">Service Fabric ist erfolgt, Aktionen, um sicherzustellen, dass der Knoten über ausreichend Kapazität verfügt.</span><span class="sxs-lookup"><span data-stu-id="9ebc0-117">Service Fabric is making actions to ensure that the node has enough capacity.</span></span> </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>