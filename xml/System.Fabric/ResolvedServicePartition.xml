<Type Name="ResolvedServicePartition" FullName="System.Fabric.ResolvedServicePartition">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServicePartition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServicePartition" />
  <TypeSignature Language="F#" Value="type ResolvedServicePartition = class" />
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
      <para>
            <span data-ttu-id="7dcd4-101">Enthält Informationen zur Partition des Diensts, der aufgelöst wurde und die Gruppe von Endpunkten, die Zugriff auf die Partition verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-101">Contains information about the partition of the service that was resolved and the set of endpoints that can be used to access the partition.</span></span></para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="7dcd4-102">Die aufgelösten Dienstpartition abgerufen wird, als Ergebnis <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> und anderen Überladungen.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-102">The resolved service partition is obtained as a result of calling <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> and the other overloads.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CompareVersion">
      <MemberSignature Language="C#" Value="public int CompareVersion (System.Fabric.ResolvedServicePartition other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 CompareVersion(class System.Fabric.ResolvedServicePartition other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareVersion (other As ResolvedServicePartition) As Integer" />
      <MemberSignature Language="F#" Value="member this.CompareVersion : System.Fabric.ResolvedServicePartition -&gt; int" Usage="resolvedServicePartition.CompareVersion other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="7dcd4-103">Die andere aufgelösten Dienstpartition, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-103">The other resolved service partition to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7dcd4-104">Vergleicht zwei aufgelösten Dienst Partitionen und identifiziert, die neuer ist.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-104">Compares two resolved service partitions and identifies which is newer.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7dcd4-105">Gibt <see cref="T:System.Int32" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-105">Returns <see cref="T:System.Int32" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="7dcd4-106">Die <see cref="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" /> -Methode übernimmt ein Argument aufgelösten Dienst Partition (RSP), mit dem Parameter <paramref name="other" /> , damit der Benutzer aus, um zu ermitteln, die RSP mehr auf dem neuesten Stand ist.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-106">The <see cref="M:System.Fabric.ResolvedServicePartition.CompareVersion(System.Fabric.ResolvedServicePartition)" /> method takes in a resolved service partition (RSP) argument with the parameter <paramref name="other" /> to enable the user to identify which RSP is more up-to-date.</span></span> <span data-ttu-id="7dcd4-107">Ein Rückgabewert von 0 gibt an, dass die zwei RSPs die gleiche Version aufweisen.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-107">A returned value of 0 indicates that the two RSPs have the same version.</span></span> <span data-ttu-id="7dcd4-108">1 gibt an, dass die anderen RSP eine ältere Version hat.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-108">1 indicates that the other RSP has an older version.</span></span> <span data-ttu-id="7dcd4-109">-1 gibt an, dass die anderen RSP eine neuere Version aufweist.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-109">-1 indicates that the other RSP has a newer version.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="7dcd4-110">Die beiden <see cref="T:System.Fabric.ResolvedServicePartition" /> Objekte aus anderen Dienst Partitionen sind.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-110">The two <see cref="T:System.Fabric.ResolvedServicePartition" /> objects are from different service partitions.</span></span> <span data-ttu-id="7dcd4-111">Dies kann geschehen, wenn der Dienst wird gelöscht und neu erstellt wird, mit dem gleichen Namen und die Trennung zwischen zwei lösen Aufrufe.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-111">This can happen if the service is deleted and re-created with the same name and partitioning between two resolve calls.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class System.Fabric.ResolvedServiceEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As ICollection(Of ResolvedServiceEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;" Usage="System.Fabric.ResolvedServicePartition.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7dcd4-112">Ruft die Endpunkte der Dienstpartition ab.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-112">Gets the endpoints of the service partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7dcd4-113">Eine Auflistung von <see cref="T:System.Fabric.ResolvedServiceEndpoint" /> für die Partition angegebenen Dienst.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-113">A collection of <see cref="T:System.Fabric.ResolvedServiceEndpoint" /> for the specified service partition.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="7dcd4-114">Ein aufgelösten Dienstendpunkt enthält die Rolle der zustandsbehafteten dienstreplikats oder einer zustandslosen Dienstinstanz und die Adresse, in denen dieses Replikat erreicht werden kann.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-114">A resolved service endpoint contains the role of the stateful service replica or stateless service instance and the address where this replica can be reached.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint GetEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.ResolvedServiceEndpoint GetEndpoint() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ResolvedServicePartition.GetEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint () As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.GetEndpoint : unit -&gt; System.Fabric.ResolvedServiceEndpoint" Usage="resolvedServicePartition.GetEndpoint " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7dcd4-115">Gibt einen einzelnen Endpunkt, anstatt eine Auflistung aller Endpunkte zurück.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-115">Returns a single endpoint, instead of a collection of all endpoints.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7dcd4-116">Gibt <see cref="T:System.Fabric.ResolvedServiceEndpoint" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-116">Returns <see cref="T:System.Fabric.ResolvedServiceEndpoint" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="7dcd4-117">In vielen Fällen benötigen Sie nur einen einzigen Endpunkt anstelle aller Endpunkte.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-117">Many times, you only need a single endpoint instead of all the endpoints.</span></span> <span data-ttu-id="7dcd4-118">Wenn der Dienst, zustandslos ist, gibt es einen zufälligen Endpunkt zurück.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-118">If the service is stateless, it returns a random endpoint.</span></span> <span data-ttu-id="7dcd4-119">Wenn der Dienst ein zustandsbehafteter Dienst ist als den Endpunkt zurückgegeben, den das primäre Replikat der Dienstpartition überwacht.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-119">If the service is a stateful service, than it returns the endpoint to which the Primary replica of the service partition listens.</span></span> <span data-ttu-id="7dcd4-120">Beachten Sie, dass das primäre Replikat derzeit nicht vorhanden ist, löst <see cref="T:System.Fabric.FabricException" />.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-120">Note that if the Primary replica currently does not exist, it throws <see cref="T:System.Fabric.FabricException" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Info">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation Info { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation Info" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.Info" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Info As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.Info : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.ResolvedServicePartition.Info" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7dcd4-121">Ruft Informationen zur Partition des Diensts, der gelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-121">Gets information about the partition of the service that was resolved.</span></span></para>
        </summary>
        <value><span data-ttu-id="7dcd4-122">Die Informationen zur Partition des Diensts, der behoben wurde.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-122">The information about the partition of the service that was resolved.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="7dcd4-123">Der Dienstpartition kann von anderen <see cref="T:System.Fabric.ServicePartitionKind" />.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-123">The service partition can be of different <see cref="T:System.Fabric.ServicePartitionKind" />.</span></span>
            <span data-ttu-id="7dcd4-124">Sie können die Informationen zur Dienstpartition in den richtigen abgeleiteten Typ zum Abrufen von ausführliche Informationen zur Partition umwandeln.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-124">You can cast the service partition information to the correct derived type to get detailed information about the partition.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ResolvedServicePartition.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7dcd4-125">Ruft den Namen der Dienstinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-125">Gets the name of the service instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7dcd4-126">Der Name der Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="7dcd4-126">The name of the service instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>