<Type Name="WcfServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class WcfServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfServiceRemotingListener&#xA;Implements ICommunicationListener, IServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingListener = class&#xA;    interface IServiceRemotingListener&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b5adb-101">Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> , verwendet Windows Communication Foundation Schnittstelle Remoting für Zustandslose und zustandsbehaftete Dienste bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="b5adb-101">An <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> that uses Windows Communication Foundation to provide interface remoting for stateless and stateful services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, System.ServiceModel.Channels.Binding listenerBinding = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, string endpointResourceName = &quot;ServiceEndpointV2&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class System.ServiceModel.Channels.Binding listenerBinding, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,System.ServiceModel.Channels.Binding,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * System.ServiceModel.Channels.Binding * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, serviceImplementation, listenerBinding, serializationProvider, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="b5adb-102">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="b5adb-102">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="serviceImplementation"><span data-ttu-id="b5adb-103">Das Dienstobjekt für die Implementierung.</span><span class="sxs-lookup"><span data-stu-id="b5adb-103">The service implementation object.</span></span></param>
        <param name="listenerBinding"><span data-ttu-id="b5adb-104">WCF-Bindung für den Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="b5adb-104">WCF binding to use for the listener.</span></span> <span data-ttu-id="b5adb-105">Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode erstellt eine <see cref="T:System.ServiceModel.NetTcpBinding" /> ohne Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="b5adb-105">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
            </param>
        <param name="serializationProvider"></param>
        <param name="endpointResourceName"><span data-ttu-id="b5adb-106">Der Name der endpunktressource definiert, in das Manifest, das verwendet werden soll, um die Adresse für den Listener zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b5adb-106">The name of the endpoint resource defined in the service manifest that should be used to create the address for the listener.</span></span> <span data-ttu-id="b5adb-107">Wenn die EndpointResourceName nicht angegebenen oder null ist, ist der Standardwert "ServiceEndpointV2" verwendet.</span><span class="sxs-lookup"><span data-stu-id="b5adb-107">If the endpointResourceName is not specified or null, the default value "ServiceEndpointV2" is used.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5adb-108">Ein WCF-Konstrukte basierend Dienst Remoting Listener.</span><span class="sxs-lookup"><span data-stu-id="b5adb-108">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, serializationProvider, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="b5adb-109">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="b5adb-109">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="messageHandler"><span data-ttu-id="b5adb-110">Der Handler für das empfangen und Verarbeiten von Nachrichten von Remoting.</span><span class="sxs-lookup"><span data-stu-id="b5adb-110">The handler for receiving and processing remoting messages.</span></span> <span data-ttu-id="b5adb-111">Beim Empfangen von Nachrichten übermittelt der Listener die Nachrichten an den Handler.</span><span class="sxs-lookup"><span data-stu-id="b5adb-111">As the messages are received the listener delivers the messages to the handler.</span></span>
            </param>
        <param name="serializationProvider"></param>
        <param name="listenerBinding"><span data-ttu-id="b5adb-112">WCF-Bindung für den Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="b5adb-112">WCF binding to use for the listener.</span></span> <span data-ttu-id="b5adb-113">Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="b5adb-113">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
            </param>
        <param name="address"><span data-ttu-id="b5adb-114">Die Endpunktadresse für den WCF-Listener verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b5adb-114">The endpoint address to use for the WCF listener.</span></span> <span data-ttu-id="b5adb-115">Wenn dies nicht der angegebenen "oder" null ", die Endpunktadresse wird erstellt unter Verwendung der Standard-Endpunkt-Ressource mit dem Namen"ServiceEndpointV2"in das Manifest definiert.</span><span class="sxs-lookup"><span data-stu-id="b5adb-115">If not specified or null, the endpoint address is created using the default endpoint resource named "ServiceEndpointV2" defined in the service manifest.</span></span> 
            </param>
        <summary>
            <span data-ttu-id="b5adb-116">Ein WCF-Konstrukte basierend Dienst Remoting Listener.</span><span class="sxs-lookup"><span data-stu-id="b5adb-116">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = &quot;ServiceEndpointV2&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, serializationProvider, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="b5adb-117">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="b5adb-117">The context of the service for which the remoting listener is being constructed.</span></span></param>
        <param name="messageHandler"><span data-ttu-id="b5adb-118">Der Handler für das empfangen und Verarbeiten von Nachrichten von Remoting.</span><span class="sxs-lookup"><span data-stu-id="b5adb-118">The handler for receiving and processing remoting messages.</span></span> <span data-ttu-id="b5adb-119">Beim Empfangen von Nachrichten übermittelt der Listener die Nachrichten an den Handler.</span><span class="sxs-lookup"><span data-stu-id="b5adb-119">As the messages are received the listener delivers the messages to the handler.</span></span>
            </param>
        <param name="serializationProvider"></param>
        <param name="listenerBinding"><span data-ttu-id="b5adb-120">WCF-Bindung für den Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="b5adb-120">WCF binding to use for the listener.</span></span> <span data-ttu-id="b5adb-121">Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode erstellt eine <see cref="T:System.ServiceModel.NetTcpBinding" /> ohne Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="b5adb-121">If the listener binding is not specified or null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method which creates a <see cref="T:System.ServiceModel.NetTcpBinding" /> with no security.</span></span>
            </param>
        <param name="endpointResourceName"><span data-ttu-id="b5adb-122">Der Name der endpunktressource definiert, in das Manifest, das verwendet werden soll, um die Adresse für den Listener zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b5adb-122">The name of the endpoint resource defined in the service manifest that should be used to create the address for the listener.</span></span> <span data-ttu-id="b5adb-123">Wenn die EndpointResourceName nicht angegeben ist, oder es null ist, ist der Standardwert "ServiceEndpointV2" verwendet.</span><span class="sxs-lookup"><span data-stu-id="b5adb-123">If the endpointResourceName is not specified or it is null, the default value "ServiceEndpointV2" is used.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5adb-124">Ein WCF-Konstrukte basierend Dienst Remoting Listener.</span><span class="sxs-lookup"><span data-stu-id="b5adb-124">Constructs a WCF based service remoting listener.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b5adb-125">Diese Methode bewirkt, dass den Listener Kommunikation zu schließen.</span><span class="sxs-lookup"><span data-stu-id="b5adb-125">This method causes the communication listener to close.</span></span> <span data-ttu-id="b5adb-126">Schließen ist ein Endstatus und diese Methode bewirkt, dass des Übergangs nicht ordnungsgemäß geschlossen.</span><span class="sxs-lookup"><span data-stu-id="b5adb-126">Close is a terminal state and this method causes the transition to close ungracefully.</span></span> <span data-ttu-id="b5adb-127">Alle ausstehenden Vorgänge (einschließlich schließen) sollte abgebrochen werden, wenn diese Methode aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="b5adb-127">Any outstanding operations (including close) should be canceled when this method is called.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="b5adb-128">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="b5adb-128">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b5adb-129">Diese Methode bewirkt, dass den Listener Kommunikation zu schließen.</span><span class="sxs-lookup"><span data-stu-id="b5adb-129">This method causes the communication listener to close.</span></span> <span data-ttu-id="b5adb-130">Schließen ist ein Endstatus und diese Methode ermöglicht die Kommunikation-Listener für den Übergang in diesen Zustand auf ordnungsgemäße Weise.</span><span class="sxs-lookup"><span data-stu-id="b5adb-130">Close is a terminal state and this method allows the communication listener to transition to this state in a graceful manner.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b5adb-131">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b5adb-131">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="b5adb-132">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="b5adb-132">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="b5adb-133">Diese Methode bewirkt, dass die Kommunikation Listener geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="b5adb-133">This method causes the communication listener to be opened.</span></span> <span data-ttu-id="b5adb-134">Nach Abschluss der öffnen, der Listener für die Kommunikation wird verwendbar - akzeptiert, und sendet Nachrichten ab.</span><span class="sxs-lookup"><span data-stu-id="b5adb-134">Once the Open completes, the communication listener becomes usable - accepts and sends messages.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b5adb-135">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="b5adb-135">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="b5adb-136">Das Ergebnis der Aufgabe ist die Endpunktzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="b5adb-136">The result of the Task is the endpoint string.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="b5adb-137">Ruft die <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="b5adb-137">Gets the <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </summary>
        <value>
                <span data-ttu-id="b5adb-138">Ein <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.</span><span class="sxs-lookup"><span data-stu-id="b5adb-138">A <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </value>
        <remarks>
                <span data-ttu-id="b5adb-139">Der Diensthost wird vom Listener in seinem Konstruktor erstellt.</span><span class="sxs-lookup"><span data-stu-id="b5adb-139">The service host is created by the listener in it's constructor.</span></span> <span data-ttu-id="b5adb-140">Bevor Sie diese Kommunikation Listener geöffnet wird, von der Laufzeit über <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> -Methode, der Diensthost durch den Zugriff auf ihn über diese Eigenschaft angepasst werden.</span><span class="sxs-lookup"><span data-stu-id="b5adb-140">Before this communication listener is opened by the runtime via <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> method, the service host can be customized by accessing it via this property.</span></span>
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>