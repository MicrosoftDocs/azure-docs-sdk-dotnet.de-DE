<Type Name="ReplicaHealthQueryDescription" FullName="System.Fabric.Description.ReplicaHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ReplicaHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ReplicaHealthQueryDescription = class" />
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
      <para><span data-ttu-id="57d08-101">Beschreibt die als abfrageeingabe für die erste <see cref="T:System.Fabric.Health.ReplicaHealth" />.</span><span class="sxs-lookup"><span data-stu-id="57d08-101">Describes the query input for getting <see cref="T:System.Fabric.Health.ReplicaHealth" />.</span></span> <span data-ttu-id="57d08-102">Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" /> verwendet.</span><span class="sxs-lookup"><span data-stu-id="57d08-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaHealthQueryDescription (Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ReplicaHealthQueryDescription.#ctor(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As Guid, replicaOrInstanceId As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ReplicaHealthQueryDescription : Guid * int64 -&gt; System.Fabric.Description.ReplicaHealthQueryDescription" Usage="new System.Fabric.Description.ReplicaHealthQueryDescription (partitionId, replicaOrInstanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="57d08-103">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="57d08-103">The partition identifier.</span></span></para>
        </param>
        <param name="replicaOrInstanceId">
          <para><span data-ttu-id="57d08-104">Die Replikat-Id mit einem zustandsbehafteten Dienst oder der statusfreien Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="57d08-104">The stateful service replica id or the stateless service instance.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="57d08-105">Instanziiert eine neue Instanz der <see cref="T:System.Fabric.Description.ReplicaHealthQueryDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="57d08-105">Instantiates a new instance of the <see cref="T:System.Fabric.Description.ReplicaHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57d08-106">Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> auf dem Replikat gemeldet.</span><span class="sxs-lookup"><span data-stu-id="57d08-106">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the replica.</span></span> <span data-ttu-id="57d08-107">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="57d08-107">Only events that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57d08-108">Die <see cref="T:System.Fabric.Health.HealthEventsFilter" /> verwendet, um die von der Abfrage zurückgegebenen Ereignisse zu filtern.</span><span class="sxs-lookup"><span data-stu-id="57d08-108">The <see cref="T:System.Fabric.Health.HealthEventsFilter" /> used to filter the events returned by query.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="57d08-109">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="57d08-109">Only events that match the filter will be returned.</span></span> <span data-ttu-id="57d08-110">Alle Ereignisse dienen zum Auswerten der Zustand des Replikats aggregiert.</span><span class="sxs-lookup"><span data-stu-id="57d08-110">All events will be used to evaluate the replica aggregated health state.</span></span>
            <span data-ttu-id="57d08-111">Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="57d08-111">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57d08-112">Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</span><span class="sxs-lookup"><span data-stu-id="57d08-112">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57d08-113">Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</span><span class="sxs-lookup"><span data-stu-id="57d08-113">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="57d08-114">Wenn nicht angegeben, verwendet der Health Store einer anwendungsintegritäts-Richtlinie für die übergeordnete Anwendung zum Auswerten der replikatintegrität an.</span><span class="sxs-lookup"><span data-stu-id="57d08-114">If not specified, the health store uses the application health policy of the parent application to evaluate the replica health.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57d08-115">Ruft den Partitionsbezeichner ab.</span><span class="sxs-lookup"><span data-stu-id="57d08-115">Gets the partition identifier.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57d08-116">Die <see cref="T:System.Guid" /> , die die Partitions-ID darstellt.</span><span class="sxs-lookup"><span data-stu-id="57d08-116">The <see cref="T:System.Guid" /> representing the partition identifier.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ReplicaHealthQueryDescription.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.Description.ReplicaHealthQueryDescription.ReplicaOrInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57d08-117">Der Replikat-Id einem zustandsbehafteten Dienst oder zustandslosen Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="57d08-117">The stateful service replica id or stateless service instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57d08-118">Die <see cref="T:System.Int64" /> , der einem zustandsbehafteten Dienst-Id oder der statusfreien Dienstinstanz darstellt.</span><span class="sxs-lookup"><span data-stu-id="57d08-118">The <see cref="T:System.Int64" /> representing the stateful service replica id or the stateless service instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ReplicaHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthQueryDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="57d08-119">Ruft eine Zeichenfolgendarstellung der Integrität abfragebeschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="57d08-119">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="57d08-120">Eine Zeichenfolgendarstellung der abfragebeschreibung Integrität.</span><span class="sxs-lookup"><span data-stu-id="57d08-120">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>