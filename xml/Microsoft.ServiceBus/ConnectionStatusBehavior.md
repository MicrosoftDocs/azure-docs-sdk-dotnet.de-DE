<Type Name="ConnectionStatusBehavior" FullName="Microsoft.ServiceBus.ConnectionStatusBehavior">
  <TypeSignature Language="C#" Value="public class ConnectionStatusBehavior : Microsoft.ServiceBus.IConnectionStatus, System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionStatusBehavior extends System.Object implements class Microsoft.ServiceBus.IConnectionStatus, class System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ConnectionStatusBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionStatusBehavior&#xA;Implements IConnectionStatus, IEndpointBehavior" />
  <TypeSignature Language="F#" Value="type ConnectionStatusBehavior = class&#xA;    interface IEndpointBehavior&#xA;    interface IConnectionStatus" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceBus.IConnectionStatus</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IEndpointBehavior</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="c11de-101">Ein Endpunktverhalten, das Zugriff auf den Verbindungsstatus von einem Dienst überwacht Azure Service Bus bietet.</span><span class="sxs-lookup"><span data-stu-id="c11de-101">An endpoint behavior that provides access to the connection status of a service listening on Azure Service Bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionStatusBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="c11de-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ConnectionStatusBehavior" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c11de-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ConnectionStatusBehavior" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connecting">
      <MemberSignature Language="C#" Value="public event EventHandler Connecting;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Connecting" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.ConnectionStatusBehavior.Connecting" />
      <MemberSignature Language="VB.NET" Value="Public Event Connecting As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Connecting : EventHandler " Usage="member this.Connecting : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceBus.IConnectionStatus.Connecting</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c11de-103">Tritt auf, wenn der Endpunkt des Relay-Diensts und bei jedem erneuten Versuch vorübergehend getrennt wird.</span><span class="sxs-lookup"><span data-stu-id="c11de-103">Occurs when the endpoint gets temporarily disconnected from the Relay Service and for each reconnect attempt.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOnline">
      <MemberSignature Language="C#" Value="public bool IsOnline { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOnline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ConnectionStatusBehavior.IsOnline" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOnline As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOnline : bool" Usage="Microsoft.ServiceBus.ConnectionStatusBehavior.IsOnline" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.IConnectionStatus.IsOnline</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c11de-104">Ruft einen Wert, der bestimmt, ob die Verbindung online ist.</span><span class="sxs-lookup"><span data-stu-id="c11de-104">Gets a value that determines if the connection is online.</span></span></summary>
        <value><span data-ttu-id="c11de-105">"true", wenn die Verbindung online ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c11de-105">true if the connection is online; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastError">
      <MemberSignature Language="C#" Value="public Exception LastError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception LastError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ConnectionStatusBehavior.LastError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastError As Exception" />
      <MemberSignature Language="F#" Value="member this.LastError : Exception" Usage="Microsoft.ServiceBus.ConnectionStatusBehavior.LastError" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.IConnectionStatus.LastError</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c11de-106">Ruft den letzten Fehler ab.</span><span class="sxs-lookup"><span data-stu-id="c11de-106">Gets the last error.</span></span></summary>
        <value><span data-ttu-id="c11de-107">Gibt eine <see cref="T:System.Exception" /> , die den letzten Fehler enthält.</span><span class="sxs-lookup"><span data-stu-id="c11de-107">Returns a <see cref="T:System.Exception" /> that contains the last error.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="public event EventHandler Offline;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Offline" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.ConnectionStatusBehavior.Offline" />
      <MemberSignature Language="VB.NET" Value="Public Event Offline As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Offline : EventHandler " Usage="member this.Offline : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceBus.IConnectionStatus.Offline</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c11de-108">Tritt auf, wenn der Endpunkt beendet wird, eine Verbindung mit dem Relaydienst herzustellen.</span><span class="sxs-lookup"><span data-stu-id="c11de-108">Occurs when the endpoint stops attempting to connect to the Relay Service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Online">
      <MemberSignature Language="C#" Value="public event EventHandler Online;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Online" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.ConnectionStatusBehavior.Online" />
      <MemberSignature Language="VB.NET" Value="Public Event Online As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Online : EventHandler " Usage="member this.Online : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceBus.IConnectionStatus.Online</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c11de-109">Tritt auf, wenn der Endpunkt wurde erfolgreich an den Relaydienst stellt eine Verbindung her.</span><span class="sxs-lookup"><span data-stu-id="c11de-109">Occurs when the endpoint successfully connects to the Relay Service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retry">
      <MemberSignature Language="C#" Value="public void Retry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retry() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.Retry" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retry ()" />
      <MemberSignature Language="F#" Value="member this.Retry : unit -&gt; unit" Usage="connectionStatusBehavior.Retry " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="c11de-110">Versucht, die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c11de-110">Retries the connection.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.AddBindingParameters (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Channels.BindingParameterCollection bindingParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Channels.BindingParameterCollection bindingParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)" />
      <MemberSignature Language="VB.NET" Value="Sub AddBindingParameters (endpoint As ServiceEndpoint, bindingParameters As BindingParameterCollection) Implements IEndpointBehavior.AddBindingParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="bindingParameters" Type="System.ServiceModel.Channels.BindingParameterCollection" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="c11de-111">Der zu verändernde Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="c11de-111">The endpoint to modify.</span></span></param>
        <param name="bindingParameters"><span data-ttu-id="c11de-112">Die Objekte, die von Bindungselementen zur Unterstützung des Verhaltens benötigt werden.</span><span class="sxs-lookup"><span data-stu-id="c11de-112">The objects that binding elements require to support the behavior.</span></span></param>
        <summary>
            <span data-ttu-id="c11de-113">Übergibt Daten zur Laufzeit an Bindungen benutzerdefiniertes Verhalten unterstützen.</span><span class="sxs-lookup"><span data-stu-id="c11de-113">Passes data at runtime to bindings to support custom behavior.</span></span> <span data-ttu-id="c11de-114">Diese Implementierung wird keine Aktion ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c11de-114">This implementation does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyClientBehavior (System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, System.ServiceModel.Dispatcher.ClientRuntime clientRuntime);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(class System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, class System.ServiceModel.Dispatcher.ClientRuntime clientRuntime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="behavior" Type="System.ServiceModel.Dispatcher.ClientRuntime" />
      </Parameters>
      <Docs>
        <param name="serviceEndpoint"><span data-ttu-id="c11de-115">Der Endpunkt, der angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="c11de-115">The endpoint that is to be customized.</span></span></param>
        <param name="clientRuntime"><span data-ttu-id="c11de-116">Die Clientlaufzeit, die angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="c11de-116">The client runtime to be customized.</span></span></param>
        <summary>
            <span data-ttu-id="c11de-117">Diese Implementierung wird keine Aktion ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c11de-117">This implementation does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyDispatchBehavior (System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(class System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, class System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="endpointDispatcher" Type="System.ServiceModel.Dispatcher.EndpointDispatcher" />
      </Parameters>
      <Docs>
        <param name="serviceEndpoint"><span data-ttu-id="c11de-118">Der Endpunkt, der angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="c11de-118">The endpoint that is to be customized.</span></span></param>
        <param name="endpointDispatcher"><span data-ttu-id="c11de-119">Der Endpunktverteiler, der geändert oder erweitert werden soll.</span><span class="sxs-lookup"><span data-stu-id="c11de-119">The endpoint dispatcher to be modified or extended.</span></span></param>
        <summary>
            <span data-ttu-id="c11de-120">Der Listener Runtime Verbindungsereignisse Status verknüpft.</span><span class="sxs-lookup"><span data-stu-id="c11de-120">Hooks up the listener runtime connection status events.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.Validate">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.Validate (System.ServiceModel.Description.ServiceEndpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.Validate(class System.ServiceModel.Description.ServiceEndpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#Validate(System.ServiceModel.Description.ServiceEndpoint)" />
      <MemberSignature Language="VB.NET" Value="Sub Validate (endpoint As ServiceEndpoint) Implements IEndpointBehavior.Validate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.Validate(System.ServiceModel.Description.ServiceEndpoint)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="c11de-121">Der Endpunkt dieses Verhalten gilt.</span><span class="sxs-lookup"><span data-stu-id="c11de-121">The endpoint this behavior applies to.</span></span></param>
        <summary>
            <span data-ttu-id="c11de-122">Diese Methode hat keine Funktion.</span><span class="sxs-lookup"><span data-stu-id="c11de-122">This method does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>