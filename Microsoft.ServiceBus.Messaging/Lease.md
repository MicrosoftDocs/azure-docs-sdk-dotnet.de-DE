<Type Name="Lease" FullName="Microsoft.ServiceBus.Messaging.Lease">
  <TypeSignature Language="C#" Value="public class Lease" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Lease extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Lease" />
  <TypeSignature Language="VB.NET" Value="Public Class Lease" />
  <TypeSignature Language="F#" Value="type Lease = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="bd5c0-101">Enthält Partitionsinformationen für den Besitz an.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-101">Contains partition ownership information.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Lease ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="bd5c0-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.Lease" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Lease (Microsoft.ServiceBus.Messaging.Lease source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Lease source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As Lease)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.Lease : Microsoft.ServiceBus.Messaging.Lease -&gt; Microsoft.ServiceBus.Messaging.Lease" Usage="new Microsoft.ServiceBus.Messaging.Lease source" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.ServiceBus.Messaging.Lease" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="bd5c0-103">Das angegebene <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> Instanz, in denen ihre Eigenschaftswerte aus kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-103">The specified <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> instance where its property values will be copied from.</span></span></param>
        <summary><span data-ttu-id="bd5c0-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> Klasse mit dem angegebenen <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> Wert als Verweis.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> class with the specified <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> value as reference.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public long Epoch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public Property Epoch As Long" />
      <MemberSignature Language="F#" Value="member this.Epoch : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5c0-105">Abrufen oder Festlegen des Jahres Epoche die Lease, d. h. ein Wert, den Sie verwenden können, um die neuesten Besitzer einer Partition zwischen konkurrierende Knoten zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-105">Gets or sets the epoch year of the lease, which is a value you can use to determine the most recent owner of a partition between competing nodes.</span></span></summary>
        <value><span data-ttu-id="bd5c0-106">Das Jahr Epoche der Lease.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-106">The epoch year of the lease.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="lease.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="bd5c0-107">Das zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-107">The object to compare.</span></span></param>
        <summary><span data-ttu-id="bd5c0-108">Bestimmt, ob diese Instanz mit dem angegebenen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-108">Determines whether this instance is equal to the specified object.</span></span></summary>
        <returns><span data-ttu-id="bd5c0-109">"true", wenn diese Instanz gleich dem angegebenen Objekt ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="bd5c0-109">true if this instance is equal to the specified object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="lease.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="bd5c0-110">Gibt den Hashcode der aktuellen Instanz zurück.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-110">Returns the hash code of the current instance.</span></span></summary>
        <returns><span data-ttu-id="bd5c0-111">Der Hashcode der aktuellen Instanz.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-111">The hash code of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public virtual bool IsExpired ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsExpired() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsExpired () As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsExpired : unit -&gt; bool&#xA;override this.IsExpired : unit -&gt; bool" Usage="lease.IsExpired " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="bd5c0-112">Bestimmt, ob die Lease abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-112">Determines whether the lease is expired.</span></span></summary>
        <returns><span data-ttu-id="bd5c0-113">"true", wenn die Lease abgelaufen ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="bd5c0-113">true if the lease is expired; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5c0-114">Ruft ab oder legt den aktuellen Wert für den Offset in den Stream.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-114">Gets or sets the current value for the offset in the stream.</span></span></summary>
        <value><span data-ttu-id="bd5c0-115">Der Lease-Offset.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-115">The lease offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Owner" />
      <MemberSignature Language="VB.NET" Value="Public Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Owner" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5c0-116">Ruft ab oder legt den Besitzer der Host für die Partition fest.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-116">Gets or sets the host owner for the partition.</span></span></summary>
        <value><span data-ttu-id="bd5c0-117">Der Host Besitzer der Partition.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-117">The host owner of the partition.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5c0-118">Ruft die ID der Partition, zu der diese Lease gehört.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-118">Gets the ID of the partition to which this lease belongs.</span></span></summary>
        <value><span data-ttu-id="bd5c0-119">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-119">The partition identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5c0-120">Ruft ab oder legt die letzte geprüften Sequenznummer im Datenstrom.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-120">Gets or sets the last checkpointed sequence number in the stream.</span></span></summary>
        <value><span data-ttu-id="bd5c0-121">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-121">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5c0-122">Abrufen oder Festlegen der Lease-Token, das Verwaltung der Parallelität zwischen Hosts.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-122">Gets or sets the lease token that manages concurrency between hosts.</span></span> <span data-ttu-id="bd5c0-123">Können Sie dieses Token garantieren einzelnen Zugriff auf alle Ressourcen, die erforderlich sind, indem Sie die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-123">You can use this token to guarantee single access to any resource needed by the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> object.</span></span></summary>
        <value><span data-ttu-id="bd5c0-124">Die Lease-Token.</span><span class="sxs-lookup"><span data-stu-id="bd5c0-124">The lease token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>