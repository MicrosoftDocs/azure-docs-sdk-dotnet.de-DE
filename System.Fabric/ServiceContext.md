<Type Name="ServiceContext" FullName="System.Fabric.ServiceContext">
  <TypeSignature Language="C#" Value="public abstract class ServiceContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceContext" />
  <TypeSignature Language="F#" Value="type ServiceContext = class" />
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
            <span data-ttu-id="b936d-101">Der Kontext, in denen der Dienst unter.</span><span class="sxs-lookup"><span data-stu-id="b936d-101">The service context that the service is operating under.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceContext (System.Fabric.NodeContext nodeContext, System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.NodeContext nodeContext, class System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceContext.#ctor(System.Fabric.NodeContext,System.Fabric.ICodePackageActivationContext,System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="F#" Value="new System.Fabric.ServiceContext : System.Fabric.NodeContext * System.Fabric.ICodePackageActivationContext * string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.ServiceContext" Usage="new System.Fabric.ServiceContext (nodeContext, codePackageActivationContext, serviceTypeName, serviceName, initializationData, partitionId, replicaOrInstanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeContext" Type="System.Fabric.NodeContext" />
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.ICodePackageActivationContext" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeContext"><span data-ttu-id="b936d-102">Der Knotenkontext, der Informationen zum Knoten enthält, in die statusfreien Dienstinstanz ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b936d-102">The node context, which contains information about the node where the stateless service instance is running.</span></span></param>
        <param name="codePackageActivationContext"><span data-ttu-id="b936d-103">Das Codepaket-Aktivierungskontext, das Informationen über das Dienstmanifest und das Paket derzeit aktivierten Code enthält, like Arbeitsverzeichnis Kontext-ID usw.</span><span class="sxs-lookup"><span data-stu-id="b936d-103">The code package activation context, which contains information from the service manifest and the currently activated code package, like work directory, context ID etc.</span></span></param>
        <param name="serviceTypeName"><span data-ttu-id="b936d-104">Der Diensttypname.</span><span class="sxs-lookup"><span data-stu-id="b936d-104">The service type name.</span></span></param>
        <param name="serviceName"><span data-ttu-id="b936d-105">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="b936d-105">The service name.</span></span></param>
        <param name="initializationData"><span data-ttu-id="b936d-106">Die Initialisierungsdaten Dienst, die angepasste Initialisierung von Daten durch den Ersteller des Diensts darstellt.</span><span class="sxs-lookup"><span data-stu-id="b936d-106">The service initialization data, which represents custom initialization data provided by the creator of the service.</span></span></param>
        <param name="partitionId"><span data-ttu-id="b936d-107">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="b936d-107">The partition ID.</span></span></param>
        <param name="replicaOrInstanceId"><span data-ttu-id="b936d-108">Das Replikat oder eine Instanz-ID an.</span><span class="sxs-lookup"><span data-stu-id="b936d-108">The replica or instance ID.</span></span></param>
        <summary>
            <span data-ttu-id="b936d-109">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ServiceContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b936d-109">Initializes a new instance of the <see cref="T:System.Fabric.ServiceContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageActivationContext">
      <MemberSignature Language="C#" Value="public System.Fabric.ICodePackageActivationContext CodePackageActivationContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ICodePackageActivationContext CodePackageActivationContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.CodePackageActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageActivationContext As ICodePackageActivationContext" />
      <MemberSignature Language="F#" Value="member this.CodePackageActivationContext : System.Fabric.ICodePackageActivationContext" Usage="System.Fabric.ServiceContext.CodePackageActivationContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ICodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="b936d-110">Ruft das Codepaket-Aktivierungskontext, das Informationen über das Dienstmanifest und das Paket derzeit aktivierten Code enthält, like Arbeitsverzeichnis Kontext-ID usw.</span><span class="sxs-lookup"><span data-stu-id="b936d-110">Gets the code package activation context, which contains information from the service manifest and the currently activated code package, like work directory, context ID etc.</span></span></para>
        </summary>
        <value><span data-ttu-id="b936d-111">Das Codepaket-Aktivierungskontext.</span><span class="sxs-lookup"><span data-stu-id="b936d-111">The code package activation context.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.ServiceContext.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b936d-112">Ruft die Initialisierungsdaten des Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="b936d-112">Gets the initialization data of the service.</span></span>
            </summary>
        <value><span data-ttu-id="b936d-113">Die Initialisierungsdaten.</span><span class="sxs-lookup"><span data-stu-id="b936d-113">The initialization data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenAddress">
      <MemberSignature Language="C#" Value="public string ListenAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ListenAddress : string" Usage="System.Fabric.ServiceContext.ListenAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b936d-114">Die Adresse, an der den Listener für die Kommunikation der Dienst gestartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b936d-114">The address at which the service should start the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b936d-115">Die Adresse, an der den Listener für die Kommunikation der Dienst gestartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b936d-115">The address at which the service should start the communication listener.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeContext">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeContext NodeContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeContext NodeContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.NodeContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeContext As NodeContext" />
      <MemberSignature Language="F#" Value="member this.NodeContext : System.Fabric.NodeContext" Usage="System.Fabric.ServiceContext.NodeContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b936d-116">Ruft die vom Knotenkontext mit Informationen über den Knoten, in dem das Replikat Dienst instanziiert wird.</span><span class="sxs-lookup"><span data-stu-id="b936d-116">Gets the node context with information about the node where the service replica is instantiated.</span></span>
            </summary>
        <value><span data-ttu-id="b936d-117">Der Knotenkontext für den Knoten, in dem die dienstreplikats oder die Instanz instanziiert wird.</span><span class="sxs-lookup"><span data-stu-id="b936d-117">The node context for the node where the service replica or instance is instantiated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.ServiceContext.PartitionId" />
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
            <span data-ttu-id="b936d-118">Ruft die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="b936d-118">Gets the partition ID.</span></span>
            </summary>
        <value><span data-ttu-id="b936d-119">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="b936d-119">The partition ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAddress">
      <MemberSignature Language="C#" Value="public string PublishAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.PublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.PublishAddress : string" Usage="System.Fabric.ServiceContext.PublishAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b936d-120">Die Adresse, die der Dienst als die abhöradresse veröffentlichen.</span><span class="sxs-lookup"><span data-stu-id="b936d-120">The address which the service should publish as the listen address.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b936d-121">Die Adresse, die der Dienst als die abhöradresse veröffentlichen.</span><span class="sxs-lookup"><span data-stu-id="b936d-121">The address which the service should publish as the listen address.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.ServiceContext.ReplicaOrInstanceId" />
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
            <span data-ttu-id="b936d-122">Ruft ab, der einem zustandsbehafteten Dienst dienstreplikats oder die ID der statusfreien Dienstinstanz-ID</span><span class="sxs-lookup"><span data-stu-id="b936d-122">Gets the stateful service replica ID or the stateless service instance ID.</span></span>
            </summary>
        <value><span data-ttu-id="b936d-123">Die Replikat-ID mit einem zustandsbehafteten Dienst oder der statusfreien Dienstinstanz-ID auf.</span><span class="sxs-lookup"><span data-stu-id="b936d-123">The stateful service replica ID or the stateless service instance ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ServiceContext.ServiceName" />
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
            <span data-ttu-id="b936d-124">Ruft den Dienstnamen.</span><span class="sxs-lookup"><span data-stu-id="b936d-124">Get the service name.</span></span>
            </summary>
        <value><span data-ttu-id="b936d-125">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="b936d-125">The service name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.ServiceContext.ServiceTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b936d-126">Ruft den Typnamen des Dienstes ab.</span><span class="sxs-lookup"><span data-stu-id="b936d-126">Gets the service type name.</span></span>
            </summary>
        <value><span data-ttu-id="b936d-127">Der Diensttypname.</span><span class="sxs-lookup"><span data-stu-id="b936d-127">The service type name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TraceId">
      <MemberSignature Language="C#" Value="public string TraceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TraceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.TraceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TraceId As String" />
      <MemberSignature Language="F#" Value="member this.TraceId : string" Usage="System.Fabric.ServiceContext.TraceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b936d-128">Ruft die Ablaufverfolgungs-ID des Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="b936d-128">Gets the trace ID of the service.</span></span>
            </summary>
        <value><span data-ttu-id="b936d-129">Die Ablaufverfolgungs-ID des Diensts.</span><span class="sxs-lookup"><span data-stu-id="b936d-129">The trace ID of the service.</span></span></value>
        <remarks><span data-ttu-id="b936d-130">Für alle generierten ablaufverfolgungen kann die Ablaufverfolgungs-ID als Bezeichner verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b936d-130">The trace ID can be used as an identifier for generated traces.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>