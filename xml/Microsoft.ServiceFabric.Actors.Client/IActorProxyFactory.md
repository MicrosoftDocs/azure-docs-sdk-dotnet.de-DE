<Type Name="IActorProxyFactory" FullName="Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory">
  <TypeSignature Language="C#" Value="public interface IActorProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorProxyFactory" />
  <TypeSignature Language="F#" Value="type IActorProxyFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1dda3-101">Definiert die Schnittstelle enthält Methoden zum Erstellen von Akteur Proxy Formularbereichsfactory-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1dda3-101">Defines the interface containing methods to create actor proxy factory class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="iActorProxyFactory.CreateActorProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            <span data-ttu-id="1dda3-102">Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-102">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="1dda3-103">Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="1dda3-103">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="serviceUri"><span data-ttu-id="1dda3-104">Der URI des Diensts Akteur.</span><span class="sxs-lookup"><span data-stu-id="1dda3-104">Uri of the actor service.</span></span></param>
        <param name="actorId"><span data-ttu-id="1dda3-105">Akteur-Id des Objekts Akteur Proxy.</span><span class="sxs-lookup"><span data-stu-id="1dda3-105">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="1dda3-106">Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="1dda3-106">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1dda3-107">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1dda3-107">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1dda3-108">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="1dda3-108">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dda3-109">Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-109">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1dda3-110">Ein Akteur-Proxy-Objekt, das IActorProxy und TActorInterface implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-110">An actor proxy object that implements IActorProxy and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="iActorProxyFactory.CreateActorProxy (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            <span data-ttu-id="1dda3-111">Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-111">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="1dda3-112">Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="1dda3-112">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="1dda3-113">Akteur-Id des Objekts Akteur Proxy.</span><span class="sxs-lookup"><span data-stu-id="1dda3-113">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="1dda3-114">Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="1dda3-114">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="applicationName">
            <span data-ttu-id="1dda3-115">Der Name der Service Fabric-Anwendung, die der Akteur-Dienst hostet die Akteur-Objekte enthält.</span><span class="sxs-lookup"><span data-stu-id="1dda3-115">Name of the Service Fabric application that contains the actor service hosting the actor objects.</span></span>
            <span data-ttu-id="1dda3-116">Dieser Parameter kann null sein, wenn der Client als Teil der gleichen Service Fabric-Anwendung ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="1dda3-116">This parameter can be null if the client is running as part of that same Service Fabric application.</span></span> <span data-ttu-id="1dda3-117">Weitere Informationen finden Sie in den Hinweisen.</span><span class="sxs-lookup"><span data-stu-id="1dda3-117">For more information, see Remarks.</span></span> 
            </param>
        <param name="serviceName">
            <span data-ttu-id="1dda3-118">Name des Service Fabric-Dienstes, je nach Konfiguration durch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> auf die Akteur-Implementierung.</span><span class="sxs-lookup"><span data-stu-id="1dda3-118">Name of the Service Fabric service as configured by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> on the actor implementation.</span></span>
            <span data-ttu-id="1dda3-119">Standardmäßig ist der Name des Diensts nicht mit dem Namen der Akteur-Schnittstelle abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="1dda3-119">By default, the name of the service is derived from the name of the actor interface.</span></span> <span data-ttu-id="1dda3-120">Jedoch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> ist erforderlich, wenn ein Akteur mehr als ein Akteur Schnittstellen implementiert oder eine Akteur-Schnittstelle wird von einer anderen Akteur-Schnittstelle abgeleitet, wie die Festlegung der ServiceName automatisch hergestellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="1dda3-120">However <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> is required when an actor implements more than one actor interfaces or an actor interface derives from another actor interface as the determination of the serviceName cannot be made automatically.</span></span>
            </param>
        <param name="listenerName">
            <span data-ttu-id="1dda3-121">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1dda3-121">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1dda3-122">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="1dda3-122">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dda3-123">Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-123">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1dda3-124">Ein Akteur-Proxy-Objekt, das IActorProxy und TActorInterface implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-124">An actor proxy object that implements IActorProxy and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iActorProxyFactory.CreateActorServiceProxy (serviceUri, actorId, listenerName)" />
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
        <typeparam name="TServiceInterface"><span data-ttu-id="1dda3-125">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</span><span class="sxs-lookup"><span data-stu-id="1dda3-125">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1dda3-126">URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1dda3-126">Uri of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="1dda3-127">Die ID des Akteurs.</span><span class="sxs-lookup"><span data-stu-id="1dda3-127">Id of the actor.</span></span> <span data-ttu-id="1dda3-128">Der erstellte Proxy wird mit der Partition des hosting mit dieser Id Akteur Akteur-Diensts verbunden sein.</span><span class="sxs-lookup"><span data-stu-id="1dda3-128">The created proxy will be connected to the partition of the actor service hosting actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1dda3-129">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1dda3-129">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1dda3-130">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="1dda3-130">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dda3-131">Erstellen Sie einen Proxy mit dem Akteur-Dienst, der Hosten der angegebenen Akteur-Id und der Dienstschnittstelle angegebenen Typ implementieren.</span><span class="sxs-lookup"><span data-stu-id="1dda3-131">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1dda3-132">Ein Dienst-Proxy-Objekt, IServiceProxy und TServiceInterface implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-132">A service proxy object that implements IServiceProxy and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateActorServiceProxy(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="iActorProxyFactory.CreateActorServiceProxy (serviceUri, partitionKey, listenerName)" />
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
        <typeparam name="TServiceInterface"><span data-ttu-id="1dda3-133">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</span><span class="sxs-lookup"><span data-stu-id="1dda3-133">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="1dda3-134">URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="1dda3-134">Uri of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="1dda3-135">Der Schlüssel des für die Verbindung der Akteur-Dienstpartition.</span><span class="sxs-lookup"><span data-stu-id="1dda3-135">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="1dda3-136">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="1dda3-136">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="1dda3-137">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="1dda3-137">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dda3-138">Erstellen Sie einen Proxy mit dem Akteur-Dienst, der Hosten der angegebenen Akteur-Id und der Dienstschnittstelle angegebenen Typ implementieren.</span><span class="sxs-lookup"><span data-stu-id="1dda3-138">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="1dda3-139">Ein Dienst-Proxy-Objekt, IServiceProxy und TServiceInterface implementiert.</span><span class="sxs-lookup"><span data-stu-id="1dda3-139">A service proxy object that implements IServiceProxy and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>