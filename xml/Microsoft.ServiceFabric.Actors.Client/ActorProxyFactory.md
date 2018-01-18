<Type Name="ActorProxyFactory" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory">
  <TypeSignature Language="C#" Value="public class ActorProxyFactory : Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorProxyFactory extends System.Object implements class Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorProxyFactory&#xA;Implements IActorProxyFactory" />
  <TypeSignature Language="F#" Value="type ActorProxyFactory = class&#xA;    interface IActorProxyFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="bffa9-101">Stellt eine Factoryklasse zum Erstellen eines Proxys für die remote Akteur-Objekte dar.</span><span class="sxs-lookup"><span data-stu-id="bffa9-101">Represents a factory class to create a proxy to the remote actor objects.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory retrySettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="retrySettings"><span data-ttu-id="bffa9-102">Wiederholen Sie die Einstellungen für das Remoteobjekt Aufrufe von Proxy.</span><span class="sxs-lookup"><span data-stu-id="bffa9-102">Retry settings for the remote object calls  made by proxy.</span></span></param>
        <summary>
            <span data-ttu-id="bffa9-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bffa9-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackClient, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory"><span data-ttu-id="bffa9-104">Factorymethode zum Erstellen von Client-Kommunikation-Remoting-Factory.</span><span class="sxs-lookup"><span data-stu-id="bffa9-104">Factory method to create remoting communication client factory.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="bffa9-105">Wiederholen Sie die Einstellungen für das Remoteobjekt Aufrufe von Proxy.</span><span class="sxs-lookup"><span data-stu-id="bffa9-105">Retry settings for the remote object calls  made by proxy.</span></span></param>
        <summary>
            <span data-ttu-id="bffa9-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> -Klasse unter Verwendung von V1 Remoting Client-Factory.</span><span class="sxs-lookup"><span data-stu-id="bffa9-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> class using V1 remoting Client Factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackMessageHandler, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory"><span data-ttu-id="bffa9-107">Factorymethode zum Erstellen von Client-Kommunikation-Remoting-Factory.</span><span class="sxs-lookup"><span data-stu-id="bffa9-107">Factory method to create remoting communication client factory.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="bffa9-108">Wiederholen Sie die Einstellungen für das Remoteobjekt Aufrufe von Proxy.</span><span class="sxs-lookup"><span data-stu-id="bffa9-108">Retry settings for the remote object calls  made by proxy.</span></span></param>
        <summary>
            <span data-ttu-id="bffa9-109">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> -Klasse unter Verwendung von Client-V2-Remoting-Factory.</span><span class="sxs-lookup"><span data-stu-id="bffa9-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> class using V2 Remoting Client Factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="bffa9-110">Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="bffa9-110">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="bffa9-111">Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="bffa9-111">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="serviceUri"><span data-ttu-id="bffa9-112">Der URI des Diensts Akteur.</span><span class="sxs-lookup"><span data-stu-id="bffa9-112">Uri of the actor service.</span></span></param>
        <param name="actorId"><span data-ttu-id="bffa9-113">Akteur-Id des Objekts Akteur Proxy.</span><span class="sxs-lookup"><span data-stu-id="bffa9-113">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="bffa9-114">Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="bffa9-114">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="bffa9-115">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="bffa9-115">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="bffa9-116">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="bffa9-116">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bffa9-117">Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.</span><span class="sxs-lookup"><span data-stu-id="bffa9-117">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="bffa9-118">Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</span><span class="sxs-lookup"><span data-stu-id="bffa9-118">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="bffa9-119">Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="bffa9-119">The actor interface implemented by the remote actor object.</span></span> <span data-ttu-id="bffa9-120">Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="bffa9-120">The returned proxy object will implement this interface.</span></span>
            </typeparam>
        <param name="actorId"><span data-ttu-id="bffa9-121">Akteur-Id des Objekts Akteur Proxy.</span><span class="sxs-lookup"><span data-stu-id="bffa9-121">Actor Id of the proxy actor object.</span></span> <span data-ttu-id="bffa9-122">Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="bffa9-122">Methods called on this proxy will result in requests being sent to the actor with this id.</span></span></param>
        <param name="applicationName">
            <span data-ttu-id="bffa9-123">Der Name der Service Fabric-Anwendung, die der Akteur-Dienst hostet die Akteur-Objekte enthält.</span><span class="sxs-lookup"><span data-stu-id="bffa9-123">Name of the Service Fabric application that contains the actor service hosting the actor objects.</span></span>
            <span data-ttu-id="bffa9-124">Dieser Parameter kann null sein, wenn der Client als Teil der gleichen Service Fabric-Anwendung ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="bffa9-124">This parameter can be null if the client is running as part of that same Service Fabric application.</span></span> <span data-ttu-id="bffa9-125">Weitere Informationen finden Sie in den Hinweisen.</span><span class="sxs-lookup"><span data-stu-id="bffa9-125">For more information, see Remarks.</span></span> 
            </param>
        <param name="serviceName">
            <span data-ttu-id="bffa9-126">Name des Service Fabric-Dienstes, je nach Konfiguration durch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> auf die Akteur-Implementierung.</span><span class="sxs-lookup"><span data-stu-id="bffa9-126">Name of the Service Fabric service as configured by <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> on the actor implementation.</span></span>
            <span data-ttu-id="bffa9-127">Standardmäßig ist der Name des Diensts nicht mit dem Namen der Akteur-Schnittstelle abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="bffa9-127">By default, the name of the service is derived from the name of the actor interface.</span></span> <span data-ttu-id="bffa9-128">Jedoch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> ist erforderlich, wenn ein Akteur mehr als ein Akteur Schnittstellen implementiert oder eine Akteur-Schnittstelle wird von einer anderen Akteur-Schnittstelle abgeleitet, wie die Festlegung der ServiceName automatisch hergestellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="bffa9-128">However <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> is required when an actor implements more than one actor interfaces or an actor interface derives from another actor interface as the determination of the serviceName cannot be made automatically.</span></span>
            </param>
        <param name="listenerName">
            <span data-ttu-id="bffa9-129">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="bffa9-129">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="bffa9-130">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="bffa9-130">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bffa9-131">Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.</span><span class="sxs-lookup"><span data-stu-id="bffa9-131">Creates a proxy to the actor object that implements an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="bffa9-132">Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</span><span class="sxs-lookup"><span data-stu-id="bffa9-132">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
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
        <typeparam name="TServiceInterface"><span data-ttu-id="bffa9-133">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</span><span class="sxs-lookup"><span data-stu-id="bffa9-133">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="bffa9-134">URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="bffa9-134">Uri of the actor service to connect to.</span></span></param>
        <param name="actorId"><span data-ttu-id="bffa9-135">Die ID des Akteurs.</span><span class="sxs-lookup"><span data-stu-id="bffa9-135">Id of the actor.</span></span> <span data-ttu-id="bffa9-136">Der erstellte Proxy wird mit der Partition des hosting mit dieser Id Akteur Akteur-Diensts verbunden sein.</span><span class="sxs-lookup"><span data-stu-id="bffa9-136">The created proxy will be connected to the partition of the actor service hosting actor with this id.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="bffa9-137">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="bffa9-137">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="bffa9-138">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="bffa9-138">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bffa9-139">Erstellen Sie einen Proxy mit dem Akteur-Dienst, der Hosten der angegebenen Akteur-Id und der Dienstschnittstelle angegebenen Typ implementieren.</span><span class="sxs-lookup"><span data-stu-id="bffa9-139">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="bffa9-140">Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und TServiceInterface.</span><span class="sxs-lookup"><span data-stu-id="bffa9-140">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateActorServiceProxy(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)</InterfaceMember>
      </Implements>
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
        <typeparam name="TServiceInterface"><span data-ttu-id="bffa9-141">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</span><span class="sxs-lookup"><span data-stu-id="bffa9-141">The service interface implemented by the actor service.</span></span></typeparam>
        <param name="serviceUri"><span data-ttu-id="bffa9-142">URI des Diensts Akteur für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="bffa9-142">Uri of the actor service to connect to.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="bffa9-143">Der Schlüssel des für die Verbindung der Akteur-Dienstpartition.</span><span class="sxs-lookup"><span data-stu-id="bffa9-143">The key of the actor service partition to connect to.</span></span></param>
        <param name="listenerName">
            <span data-ttu-id="bffa9-144">Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.</span><span class="sxs-lookup"><span data-stu-id="bffa9-144">By default an actor service has only one listener for clients to connect to and communicate with.</span></span>
            <span data-ttu-id="bffa9-145">Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="bffa9-145">However it is possible to configure an actor service with more than one listeners, the listenerName parameter specifies the name of the listener to connect to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bffa9-146">Erstellen Sie einen Proxy mit dem Akteur-Dienst, der Hosten der angegebenen Akteur-Id und der Dienstschnittstelle angegebenen Typ implementieren.</span><span class="sxs-lookup"><span data-stu-id="bffa9-146">Create a proxy to the actor service that is hosting the specified actor id and implementing specified type of the service interface.</span></span>
            </summary>
        <returns><span data-ttu-id="bffa9-147">Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und TServiceInterface.</span><span class="sxs-lookup"><span data-stu-id="bffa9-147">A service proxy object that implements <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> and TServiceInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>