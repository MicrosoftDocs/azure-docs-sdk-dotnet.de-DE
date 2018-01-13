<Type Name="ActorServiceProxy" FullName="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy">
  <TypeSignature Language="C#" Value="public sealed class ActorServiceProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorServiceProxy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorServiceProxy" />
  <TypeSignature Language="F#" Value="type ActorServiceProxy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c71c-101">Stellt einen Proxy, der von Clients zum interagieren mit dem Akteur-Dienst in einem Service Fabric-Cluster ausgeführt, und führen Sie die Ebene Akteur Dienstvorgänge verwendet.</span><span class="sxs-lookup"><span data-stu-id="1c71c-101">Provides a Proxy used by clients to interact with the actor service running in a Service Fabric cluster and perform actor service level operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1c71c-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1c71c-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.IActorService Create (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.IActorService Create(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; Microsoft.ServiceFabric.Actors.IActorService" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.IActorService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="1c71c-103">Der URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-103">The URI of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="1c71c-104">Die ID des Akteurs.</span><span class="sxs-lookup"><span data-stu-id="1c71c-104">The ID of the actor.</span></span> <span data-ttu-id="1c71c-105">Der erstellte Proxy werden mit der Partition des Diensts Akteur hosting des Akteurs mit dieser ID verbunden.</span><span class="sxs-lookup"><span data-stu-id="1c71c-105">The created proxy will be connected to the partition of the actor service hosting the actor with this ID.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1c71c-106">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1c71c-106">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1c71c-107">Allerdings ist es möglich, mehrere Listener einen Akteur-Dienst konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="1c71c-107">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1c71c-108">Dieser Parameter gibt den Namen des Listeners für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-108">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c71c-109">Erstellt einen Proxy für die Akteur-Dienst, der den angegebenen Typ der Akteur und implementieren den angegebenen Typ der Dienstschnittstelle gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="1c71c-109">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1c71c-110">Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und <see cref="T:Microsoft.ServiceFabric.Actors.IActorService" /> Schnittstellen.</span><span class="sxs-lookup"><span data-stu-id="1c71c-110">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and <see cref="T:Microsoft.ServiceFabric.Actors.IActorService" /> interfaces.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.IActorService Create (Uri serviceUri, long partitionKey, string listenerName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.IActorService Create(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As IActorService" />
      <MemberSignature Language="F#" Value="static member Create : Uri * int64 * string -&gt; Microsoft.ServiceFabric.Actors.IActorService" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.IActorService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="1c71c-111">Der URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-111">The URI of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="1c71c-112">Der Schlüssel des für die Verbindung der Akteur-Dienstpartition.</span><span class="sxs-lookup"><span data-stu-id="1c71c-112">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1c71c-113">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1c71c-113">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1c71c-114">Allerdings ist es möglich, mehrere Listener einen Akteur-Dienst konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="1c71c-114">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1c71c-115">Dieser Parameter gibt den Namen des Listeners für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-115">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c71c-116">Erstellt einen Proxy für die Akteur-Dienst, der den angegebenen Typ der Akteur und implementieren den angegebenen Typ der Dienstschnittstelle gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="1c71c-116">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1c71c-117">Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und <see cref="T:Microsoft.ServiceFabric.Actors.IActorService" /> Schnittstellen.</span><span class="sxs-lookup"><span data-stu-id="1c71c-117">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and <see cref="T:Microsoft.ServiceFabric.Actors.IActorService" /> interfaces.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public static TServiceInterface Create&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TServiceInterface Create&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface"><span data-ttu-id="1c71c-118">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</span><span class="sxs-lookup"><span data-stu-id="1c71c-118">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1c71c-119">Der URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-119">The URI of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="1c71c-120">Die ID des Akteurs.</span><span class="sxs-lookup"><span data-stu-id="1c71c-120">The ID of the actor.</span></span> <span data-ttu-id="1c71c-121">Der erstellte Proxy werden mit der Partition des Diensts Akteur hosting des Akteurs mit dieser ID verbunden.</span><span class="sxs-lookup"><span data-stu-id="1c71c-121">The created proxy will be connected to the partition of the actor service hosting the actor with this ID.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1c71c-122">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1c71c-122">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1c71c-123">Allerdings ist es möglich, mehrere Listener einen Akteur-Dienst konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="1c71c-123">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1c71c-124">Dieser Parameter gibt den Namen des Listeners für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-124">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c71c-125">Erstellt einen Proxy für die Akteur-Dienst, der den angegebenen Typ der Akteur und implementieren den angegebenen Typ der Dienstschnittstelle gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="1c71c-125">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1c71c-126">Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und TServiceInterface.</span><span class="sxs-lookup"><span data-stu-id="1c71c-126">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public static TServiceInterface Create&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TServiceInterface Create&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="static member Create : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorServiceProxy.Create (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface"><span data-ttu-id="1c71c-127">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</span><span class="sxs-lookup"><span data-stu-id="1c71c-127">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1c71c-128">Der URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-128">The URI of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="1c71c-129">Der Schlüssel des für die Verbindung der Akteur-Dienstpartition.</span><span class="sxs-lookup"><span data-stu-id="1c71c-129">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1c71c-130">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1c71c-130">By default, an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1c71c-131">Allerdings ist es möglich, mehrere Listener einen Akteur-Dienst konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="1c71c-131">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="1c71c-132">Dieser Parameter gibt den Namen des Listeners für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1c71c-132">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c71c-133">Erstellt einen Proxy für die Akteur-Dienst, der den angegebenen Typ der Akteur und implementieren den angegebenen Typ der Dienstschnittstelle gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="1c71c-133">Creates a proxy to the actor service that is hosting the specified type of actor and implementing the specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1c71c-134">Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und TServiceInterface.</span><span class="sxs-lookup"><span data-stu-id="1c71c-134">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>