<Type Name="ActorProxy" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxy">
  <TypeSignature Language="C#" Value="public abstract class ActorProxy : Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase, Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorProxy extends Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase implements class Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorProxy&#xA;Inherits ProxyBase&#xA;Implements IActorProxy" />
  <TypeSignature Language="F#" Value="type ActorProxy = class&#xA;    inherit ProxyBase&#xA;    interface IActorProxy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b9533-101">Stellt die basisimplementierung für den Proxy für die remote Akteur-Objekte implementieren <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> Schnittstellen.</span><span class="sxs-lookup"><span data-stu-id="b9533-101">Provides the base implementation for the proxy to the remote actor objects implementing <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> interfaces.</span></span>
            <span data-ttu-id="b9533-102">Die Proxy-Objekt kann für die Client-zu-Akteur und jede Akteur-Akteur-Kommunikation verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b9533-102">The proxy object can be used used for client-to-actor and actor-to-actor communication.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ActorProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b9533-103">Initialisiert eine neue Instanz der ActorProxy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b9533-103">Initializes a new instance of the ActorProxy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9533-104">Ruft <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> Proxy-Objekt zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="b9533-104">Gets <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> associated with the proxy object.</span></span>
            </summary>
        <value>
          <span data-ttu-id="b9533-105"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />die Proxy-Objekt zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="b9533-105"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> associated with the proxy object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClient As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClient : Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClient</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9533-106">Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> -Schnittstelle, die diesen Proxy für die Kommunikation mit dem Akteur verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="b9533-106">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> interface that this proxy is using to communicate with the actor.</span></span>
            </summary>
        <value>
          <span data-ttu-id="b9533-107"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />mit diesen Proxy für die Kommunikation mit dem Akteur.</span><span class="sxs-lookup"><span data-stu-id="b9533-107"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClientV2">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClientV2 As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClientV2 : Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClientV2</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9533-108">Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> -Schnittstelle, die diesen Proxy für die Kommunikation mit dem Akteur verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="b9533-108">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> interface that this proxy is using to communicate with the actor.</span></span>
            </summary>
        <value>
          <span data-ttu-id="b9533-109"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />mit diesen Proxy für die Kommunikation mit dem Akteur.</span><span class="sxs-lookup"><span data-stu-id="b9533-109"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, Uri serviceUri, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Uri serviceUri, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.Uri,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * Uri * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, serviceUri, listenerName)" />
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
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            <span data-ttu-id="b9533-110">Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="b9533-110">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="b9533-111">Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="b9533-111">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="b9533-112">Akteur-Id des Objekts Akteur Proxy.</span><span class="sxs-lookup"><span data-stu-id="b9533-112">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="b9533-113">Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="b9533-113">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="serviceUri"><span data-ttu-id="b9533-114">Der URI des Diensts Akteur.</span><span class="sxs-lookup"><span data-stu-id="b9533-114">Uri of the actor service.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="b9533-115">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="b9533-115">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="b9533-116">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="b9533-116">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9533-117">Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.</span><span class="sxs-lookup"><span data-stu-id="b9533-117">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="b9533-118">Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</span><span class="sxs-lookup"><span data-stu-id="b9533-118">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, applicationName, serviceName, listenerName)" />
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
            <span data-ttu-id="b9533-119">Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="b9533-119">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="b9533-120">Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="b9533-120">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="b9533-121">Die Akteur-ID des Objekts Akteur Proxy.</span><span class="sxs-lookup"><span data-stu-id="b9533-121">The actor ID of the proxy actor object.</span></span> <span data-ttu-id="b9533-122">Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser ID gesendet werden</span><span class="sxs-lookup"><span data-stu-id="b9533-122">Methods called on this proxy will result in requests being sent to the actor with this ID.</span></span></param>
        <param name="applicationName">
            <span data-ttu-id="b9533-123">Der Name der Service Fabric-Anwendung, die der Akteur-Dienst hostet die Akteur-Objekte enthält.</span><span class="sxs-lookup"><span data-stu-id="b9533-123">The name of the Service Fabric application that contains the actor service hosting the actor objects.</span></span>
            <span data-ttu-id="b9533-124">Dieser Parameter kann null sein, wenn der Client als Teil der gleichen Service Fabric-Anwendung ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b9533-124">This parameter can be null if the client is running as part of that same Service Fabric application.</span></span> <span data-ttu-id="b9533-125">Weitere Informationen finden Sie in den Hinweisen.</span><span class="sxs-lookup"><span data-stu-id="b9533-125">For more information, see Remarks.</span></span> 
            </param>
        <param name="serviceName">
            <span data-ttu-id="b9533-126">Der Name des Service Fabric-Dienstes, je nach Konfiguration durch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> auf die Akteur-Implementierung.</span><span class="sxs-lookup"><span data-stu-id="b9533-126">The name of the Service Fabric service as configured by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> on the actor implementation.</span></span>
            <span data-ttu-id="b9533-127">Standardmäßig ist der Name des Diensts nicht mit dem Namen der Akteur-Schnittstelle abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="b9533-127">By default, the name of the service is derived from the name of the actor interface.</span></span> <span data-ttu-id="b9533-128">Allerdings <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> ist erforderlich, wenn ein Akteur mehr als ein Akteur Schnittstelle implementiert wird oder eine Akteur-Schnittstelle von einer anderen Akteur-Schnittstelle abgeleitet wird, da der Dienstname automatisch ermittelt werden kann.</span><span class="sxs-lookup"><span data-stu-id="b9533-128">However, <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> is required when an actor implements more than one actor interface or an actor interface derives from another actor interface since the service name cannot be determined automatically.</span></span>
            </param>
        <param name="listenerName">
            <span data-ttu-id="b9533-129">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="b9533-129">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="b9533-130">Allerdings ist es möglich, mehrere Listener einen Akteur-Dienst konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="b9533-130">However, it is possible to configure an actor service with more than one listener.</span></span> <span data-ttu-id="b9533-131">Dieser Parameter gibt den Namen des Listeners für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="b9533-131">This parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9533-132">Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.</span><span class="sxs-lookup"><span data-stu-id="b9533-132">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="b9533-133">Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</span><span class="sxs-lookup"><span data-stu-id="b9533-133">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="b9533-134">Der Parameter "ApplicationName" ist null, wenn der Client als Teil der gleichen Service Fabric-Anwendung als Akteur-Dienst ausgeführt wird, für die Kommunikation mit beibehält.</span><span class="sxs-lookup"><span data-stu-id="b9533-134">The applicationName parameter can be null if the client is running as part of the same Service Fabric application as the actor service it intends to communicate with.</span></span> <span data-ttu-id="b9533-135">In diesem Fall wird der Anwendungsname aus bestimmt <see cref="T:System.Fabric.CodePackageActivationContext" />, und erfolgt durch Aufrufen über die <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="b9533-135">In this case, the application name is determined from <see cref="T:System.Fabric.CodePackageActivationContext" />, and is obtained by calling the <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" /> property.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>