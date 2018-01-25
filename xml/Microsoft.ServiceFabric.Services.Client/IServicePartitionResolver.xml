<Type Name="IServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver">
  <TypeSignature Language="C#" Value="public interface IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type IServicePartitionResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="4ef91-101">Definiert die Schnittstelle für die Partition-Konfliktlöser.</span><span class="sxs-lookup"><span data-stu-id="4ef91-101">Defines the interface for the Service partition resolver.</span></span>
            <span data-ttu-id="4ef91-102">Dienst-Auflösung versteht man die Gruppe von Endpunkten für die Replikate in einer Partition nachschlagen.</span><span class="sxs-lookup"><span data-stu-id="4ef91-102">Service resolution is the process of looking up the set of endpoints for the replicas in a partition.</span></span> <span data-ttu-id="4ef91-103">Ein Partition-Konfliktlöser implementiert die Logik zur Auflösung des Diensts.</span><span class="sxs-lookup"><span data-stu-id="4ef91-103">A service partition resolver implements the logic for service resolution.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="4ef91-104">Die aufgelösten Dienstpartition, die der Client über den früheren Aufruf der Methode ResolveAsync() erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="4ef91-104">The resolved service partition that the client got from the earlier invocation of the ResolveAsync() method.</span></span></param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="4ef91-105">Versuchen Sie, das Timeout pro auflösen.</span><span class="sxs-lookup"><span data-stu-id="4ef91-105">The timeout per resolve try.</span></span></param>
        <param name="maxRetryBackoffInterval">
            <span data-ttu-id="4ef91-106">Das Intervall, und wiederholen Sie dann die Auflösung nach einem Fehler aufgrund einer Ausnahme mit möglichem Wiederholungsversuch Backoff.</span><span class="sxs-lookup"><span data-stu-id="4ef91-106">The interval to back-off before retrying the resolution after a failure due to retry-able exception.</span></span>
            </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="4ef91-107">Das CancellationToken, das diesen Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="4ef91-107">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="4ef91-108">Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4ef91-108">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="4ef91-109">Löst erneut eine zuvor aufgelöste Partition des angegebenen Diensts mit den angegebenen Back-off/wiederholen-Einstellungen auf Fehler mit möglichem Wiederholungsversuch auf.</span><span class="sxs-lookup"><span data-stu-id="4ef91-109">Re-resolves a previously resolved partition of the specified service with specified back-off/retry settings on retry-able errors.</span></span> <span data-ttu-id="4ef91-110">Diese methodenüberladung ist in Fällen verwendet, in dem der Client weiß, dass die aufgelösten Dienstpartition, die nicht mehr gültig ist.</span><span class="sxs-lookup"><span data-stu-id="4ef91-110">This method overload is used in cases where the client knows that the resolved service partition that it has is no longer valid.</span></span>
            </para>
        </summary>
        <returns>
            <span data-ttu-id="4ef91-111">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , Auflösungsvorgang ausstehende Dienst darstellt.</span><span class="sxs-lookup"><span data-stu-id="4ef91-111">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding service resolution operation.</span></span> <span data-ttu-id="4ef91-112">Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.</span><span class="sxs-lookup"><span data-stu-id="4ef91-112">The result from the Task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="4ef91-113">Der Name der Dienstinstanz zu beheben.</span><span class="sxs-lookup"><span data-stu-id="4ef91-113">Name of the service instance to resolve.</span></span></param>
        <param name="partitionKey">
          <para>
            <span data-ttu-id="4ef91-114"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Schlüssel</see> , bestimmt die Zielpartition der Dienstinstanz.</span><span class="sxs-lookup"><span data-stu-id="4ef91-114"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Key</see> that determines the target partition of the service instance.</span></span> <span data-ttu-id="4ef91-115">Die <see cref="T:System.Fabric.ServicePartitionKind">Partitionsschema</see> angegeben im Schlüssel sollten Übereinstimmung das Partitionierungsschema verwendet, um die Instanz zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4ef91-115">The <see cref="T:System.Fabric.ServicePartitionKind">partitioning scheme</see> specified in the key should match the partitioning scheme used to create the service instance.</span></span>
            </para>
        </param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="4ef91-116">Versuchen Sie, das Timeout pro auflösen.</span><span class="sxs-lookup"><span data-stu-id="4ef91-116">The timeout per resolve try.</span></span></param>
        <param name="maxRetryBackoffInterval">
            <span data-ttu-id="4ef91-117">Das Intervall, und wiederholen Sie dann die Auflösung nach einem Fehler aufgrund einer Ausnahme mit möglichem Wiederholungsversuch Backoff.</span><span class="sxs-lookup"><span data-stu-id="4ef91-117">The interval to back-off before retrying the resolution after a failure due to retry-able exception.</span></span>
            </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="4ef91-118">Das CancellationToken, das diesen Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="4ef91-118">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="4ef91-119">Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4ef91-119">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="4ef91-120">Löst eine Partition des angegebenen Diensts mit den angegebenen Back-off/wiederholen-Einstellungen auf Fehler mit möglichem Wiederholungsversuch auf.</span><span class="sxs-lookup"><span data-stu-id="4ef91-120">Resolves a partition of the specified service with specified back-off/retry settings on retry-able errors.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ef91-121">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , die die ausstehenden Auflösung Dienstvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="4ef91-121">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents the outstanding service resolution operation.</span></span> <span data-ttu-id="4ef91-122">Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.</span><span class="sxs-lookup"><span data-stu-id="4ef91-122">The result from the Task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>