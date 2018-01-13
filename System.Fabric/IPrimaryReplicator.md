<Type Name="IPrimaryReplicator" FullName="System.Fabric.IPrimaryReplicator">
  <TypeSignature Language="C#" Value="public interface IPrimaryReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPrimaryReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IPrimaryReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPrimaryReplicator" />
  <TypeSignature Language="F#" Value="type IPrimaryReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="c6989-101">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-101">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BuildReplicaAsync (System.Fabric.ReplicaInformation replicaInfo, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BuildReplicaAsync(class System.Fabric.ReplicaInformation replicaInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IPrimaryReplicator.BuildReplicaAsync(System.Fabric.ReplicaInformation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BuildReplicaAsync : System.Fabric.ReplicaInformation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iPrimaryReplicator.BuildReplicaAsync (replicaInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaInfo" Type="System.Fabric.ReplicaInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaInfo">
          <para><span data-ttu-id="c6989-102">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-102">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c6989-103">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c6989-103">The <see cref="T:System.Threading.CancellationToken" />  object that the operation is observing.</span></span> <span data-ttu-id="c6989-104">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c6989-104">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="c6989-105">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c6989-105">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="c6989-106">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-106">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="c6989-107">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c6989-107">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IPrimaryReplicator.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iPrimaryReplicator.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="c6989-108">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c6989-108">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="c6989-109">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c6989-109">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="c6989-110">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c6989-110">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="c6989-111">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-111">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="c6989-112">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c6989-112">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplica">
      <MemberSignature Language="C#" Value="public void RemoveReplica (long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveReplica(int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IPrimaryReplicator.RemoveReplica(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveReplica (replicaId As Long)" />
      <MemberSignature Language="F#" Value="abstract member RemoveReplica : int64 -&gt; unit" Usage="iPrimaryReplicator.RemoveReplica replicaId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="replicaId">
          <para><span data-ttu-id="c6989-113">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-113">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <summary><span data-ttu-id="c6989-114">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-114">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>
          <para><span data-ttu-id="c6989-115">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-115">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCatchUpReplicaSetConfiguration">
      <MemberSignature Language="C#" Value="public void UpdateCatchUpReplicaSetConfiguration (System.Fabric.ReplicaSetConfiguration currentConfiguration, System.Fabric.ReplicaSetConfiguration previousConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateCatchUpReplicaSetConfiguration(class System.Fabric.ReplicaSetConfiguration currentConfiguration, class System.Fabric.ReplicaSetConfiguration previousConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration,System.Fabric.ReplicaSetConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateCatchUpReplicaSetConfiguration (currentConfiguration As ReplicaSetConfiguration, previousConfiguration As ReplicaSetConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCatchUpReplicaSetConfiguration : System.Fabric.ReplicaSetConfiguration * System.Fabric.ReplicaSetConfiguration -&gt; unit" Usage="iPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration (currentConfiguration, previousConfiguration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
        <Parameter Name="previousConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
      </Parameters>
      <Docs>
        <param name="currentConfiguration">
          <para><span data-ttu-id="c6989-116">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="c6989-116">For Internal Use Only.</span></span></para>
        </param>
        <param name="previousConfiguration">
          <para><span data-ttu-id="c6989-117">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="c6989-117">For Internal Use Only.</span></span></para>
        </param>
        <summary><span data-ttu-id="c6989-118">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-118">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCurrentReplicaSetConfiguration">
      <MemberSignature Language="C#" Value="public void UpdateCurrentReplicaSetConfiguration (System.Fabric.ReplicaSetConfiguration currentConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateCurrentReplicaSetConfiguration(class System.Fabric.ReplicaSetConfiguration currentConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateCurrentReplicaSetConfiguration (currentConfiguration As ReplicaSetConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCurrentReplicaSetConfiguration : System.Fabric.ReplicaSetConfiguration -&gt; unit" Usage="iPrimaryReplicator.UpdateCurrentReplicaSetConfiguration currentConfiguration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
      </Parameters>
      <Docs>
        <param name="currentConfiguration">
          <para><span data-ttu-id="c6989-119">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-119">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <summary><span data-ttu-id="c6989-120">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-120">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>
          <para><span data-ttu-id="c6989-121">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-121">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForCatchUpQuorumAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task WaitForCatchUpQuorumAsync (System.Fabric.ReplicaSetQuorumMode quorumMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task WaitForCatchUpQuorumAsync(valuetype System.Fabric.ReplicaSetQuorumMode quorumMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IPrimaryReplicator.WaitForCatchUpQuorumAsync(System.Fabric.ReplicaSetQuorumMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WaitForCatchUpQuorumAsync : System.Fabric.ReplicaSetQuorumMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iPrimaryReplicator.WaitForCatchUpQuorumAsync (quorumMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="quorumMode" Type="System.Fabric.ReplicaSetQuorumMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="quorumMode">
          <para><span data-ttu-id="c6989-122">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="c6989-122">For Internal Use Only.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c6989-123">Das CancellationToken-Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c6989-123">The CancellationToken object that the operation is observing.</span></span> <span data-ttu-id="c6989-124">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c6989-124">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="c6989-125">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c6989-125">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="c6989-126">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6989-126">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="c6989-127">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="c6989-127">For Internal Use Only.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>