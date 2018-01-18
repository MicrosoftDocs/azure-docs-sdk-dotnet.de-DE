<Type Name="IReplicator" FullName="System.Fabric.IReplicator">
  <TypeSignature Language="C#" Value="public interface IReplicator : System.Fabric.IPrimaryReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReplicator implements class System.Fabric.IPrimaryReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReplicator&#xA;Implements IPrimaryReplicator" />
  <TypeSignature Language="F#" Value="type IReplicator = interface&#xA;    interface IPrimaryReplicator" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IPrimaryReplicator</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="a267d-101">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-101">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iReplicator.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a267d-102">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-102">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeRoleAsync (System.Fabric.Epoch epoch, System.Fabric.ReplicaRole role, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ChangeRoleAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Fabric.ReplicaRole role, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.ChangeRoleAsync(System.Fabric.Epoch,System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.Epoch * System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.ChangeRoleAsync (epoch, role, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="role" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="a267d-103">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-103">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="role">
          <para><span data-ttu-id="a267d-104">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-104">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="a267d-105">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a267d-105">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="a267d-106">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a267d-106">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="a267d-107">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a267d-107">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="a267d-108">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-108">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="a267d-109">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a267d-109">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="a267d-110">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a267d-110">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="a267d-111">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a267d-111">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="a267d-112">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a267d-112">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="a267d-113">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-113">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="a267d-114">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a267d-114">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCatchUpCapability">
      <MemberSignature Language="C#" Value="public long GetCatchUpCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetCatchUpCapability() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.GetCatchUpCapability" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCatchUpCapability () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetCatchUpCapability : unit -&gt; int64" Usage="iReplicator.GetCatchUpCapability " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a267d-115">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-115">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="a267d-116">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="a267d-116">For Internal Use Only.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentProgress">
      <MemberSignature Language="C#" Value="public long GetCurrentProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetCurrentProgress() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.GetCurrentProgress" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentProgress () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetCurrentProgress : unit -&gt; int64" Usage="iReplicator.GetCurrentProgress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a267d-117">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-117">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="a267d-118">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-118">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iReplicator.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="a267d-119">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a267d-119">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="a267d-120">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a267d-120">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="a267d-121">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a267d-121">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="a267d-122">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-122">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="a267d-123">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a267d-123">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpochAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateEpochAsync (System.Fabric.Epoch epoch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEpochAsync : System.Fabric.Epoch * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.UpdateEpochAsync (epoch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="a267d-124">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-124">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="a267d-125">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a267d-125">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="a267d-126">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a267d-126">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="a267d-127">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a267d-127">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="a267d-128">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-128">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="a267d-129">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a267d-129">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>