<Type Name="ReplicaRole" FullName="System.Fabric.ReplicaRole">
  <TypeSignature Language="C#" Value="public enum ReplicaRole" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReplicaRole extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicaRole" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReplicaRole" />
  <TypeSignature Language="F#" Value="type ReplicaRole = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="32ecc-101">Gibt die Rolle eines zustandsbehafteten dienstreplikats an.</span><span class="sxs-lookup"><span data-stu-id="32ecc-101">Indicates the role of a stateful service replica.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="32ecc-102">Service Fabric ist aus einem Replikat Dienst abhängig von der derzeit ausgeführten Rolle unterschiedliche Verhaltensweisen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="32ecc-102">Service Fabric requires different behaviors from a service replica depending on what role it currently performs.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActiveSecondary">
      <MemberSignature Language="C#" Value="ActiveSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole ActiveSecondary = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.ActiveSecondary" />
      <MemberSignature Language="VB.NET" Value="ActiveSecondary" />
      <MemberSignature Language="F#" Value="ActiveSecondary = 4" Usage="System.Fabric.ReplicaRole.ActiveSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="32ecc-103">Bezieht sich auf ein Replikat in der Gruppe, die statusaktualisierungen vom primären Replikat empfängt, anwendet und Bestätigungen zurücksendet.</span><span class="sxs-lookup"><span data-stu-id="32ecc-103">Refers to a replica in the set that receives state updates from the Primary replica, applies them, and sends acknowledgements back.</span></span> <span data-ttu-id="32ecc-104">Sekundäre Replikate müssen am schreibquorum für eine Replikatgruppe teilnehmen.</span><span class="sxs-lookup"><span data-stu-id="32ecc-104">Secondary replicas must participate in the write quorum for a replica set.</span></span> <span data-ttu-id="32ecc-105">Es können mehrere aktive sekundäre Replikate in einer Replikatgruppe zu einem Zeitpunkt vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="32ecc-105">There can be multiple active Secondary replicas in a replica set at a time.</span></span> <span data-ttu-id="32ecc-106">Die Anzahl der aktiven sekundären Replikate ist konfigurierbar, dass es sich bei das für systemzuverlässigkeit eingesetzten Subsystem verwalten soll.</span><span class="sxs-lookup"><span data-stu-id="32ecc-106">The number of active Secondary replicas is configurable that the reliability subsystem should maintain.</span></span>  </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="IdleSecondary">
      <MemberSignature Language="C#" Value="IdleSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole IdleSecondary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.IdleSecondary" />
      <MemberSignature Language="VB.NET" Value="IdleSecondary" />
      <MemberSignature Language="F#" Value="IdleSecondary = 3" Usage="System.Fabric.ReplicaRole.IdleSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="32ecc-107">Bezieht sich auf ein Replikat in der Gruppe, die eine Übertragung Zustand vom primären Replikat zur Vorbereitung der immer als aktives sekundäres Replikat empfängt.</span><span class="sxs-lookup"><span data-stu-id="32ecc-107">Refers to a replica in the set that receives a state transfer from the Primary replica to prepare for becoming an active Secondary replica.</span></span> <span data-ttu-id="32ecc-108">Es können mehrere inaktive sekundäre Replikate in einer Replikatgruppe zu einem Zeitpunkt vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="32ecc-108">There can be multiple Idle Secondary replicas in a replica set at a time.</span></span> <span data-ttu-id="32ecc-109">Inaktive sekundäre Replikate werden nicht als Teil eines schreibquorums gezählt.</span><span class="sxs-lookup"><span data-stu-id="32ecc-109">Idle Secondary replicas do not count as a part of a write quorum.</span></span> </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.ReplicaRole.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="32ecc-110">Gibt an, dass das Replikat keine Verantwortung hinsichtlich der Replikatgruppe aufweist.</span><span class="sxs-lookup"><span data-stu-id="32ecc-110">Specifies that the replica has no responsibility in regard to the replica set.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="32ecc-111">Wenn <see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" /> gibt dieser Rolle kann gefahrlos alle persistenten Status zu löschen, die dieses Replikat zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="32ecc-111">When <see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" /> indicates this role, it is safe to delete any persistent state that is associated with this replica.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="Primary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole Primary = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.Primary" />
      <MemberSignature Language="VB.NET" Value="Primary" />
      <MemberSignature Language="F#" Value="Primary = 2" Usage="System.Fabric.ReplicaRole.Primary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="32ecc-112">Bezieht sich auf das Replikat in der, das Gruppe auf das alle Lese- und Schreibzugriff Operations um Semantik mit starker Konsistenz durchzusetzen abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="32ecc-112">Refers to the replica in the set on which all read and write operations are complete in order to enforce strong consistency semantics.</span></span> <span data-ttu-id="32ecc-113">Lesevorgänge werden direkt vom primären Replikat verarbeitet, während Schreibvorgänge durch ein Quorum der Replikate in der Replikatgruppe bestätigt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="32ecc-113">Read operations are handled directly by the Primary replica, while write operations must be acknowledged by a quorum of the replicas in the replica set.</span></span> <span data-ttu-id="32ecc-114">Es kann nur ein primäres Replikat in einer Replikatgruppe zu einem Zeitpunkt vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="32ecc-114">There can only be one Primary replica in a replica set at a time.</span></span> </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReplicaRole Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReplicaRole.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="System.Fabric.ReplicaRole.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="32ecc-115">Gibt die erste Rolle, der in ein Replikat erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="32ecc-115">Indicates the initial role that a replica is created in.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>