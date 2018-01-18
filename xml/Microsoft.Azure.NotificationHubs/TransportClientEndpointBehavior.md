<Type Name="TransportClientEndpointBehavior" FullName="Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior">
  <TypeSignature Language="C#" Value="public sealed class TransportClientEndpointBehavior : System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TransportClientEndpointBehavior extends System.Object implements class System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TransportClientEndpointBehavior&#xA;Implements IEndpointBehavior" />
  <TypeSignature Language="F#" Value="type TransportClientEndpointBehavior = class&#xA;    interface IEndpointBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IEndpointBehavior</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="97c8d-101">Beschreibt das Verhalten der WCF-Endpunkt ab, das die Service Bus-Anmeldeinformationen für einen bestimmten Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="97c8d-101">Describes the WCF endpoint behavior that is used to specify the Service Bus credentials for a particular endpoint.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransportClientEndpointBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="97c8d-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="97c8d-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransportClientEndpointBehavior (Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.#ctor(Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior : Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" Usage="new Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior tokenProvider" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="tokenProvider"><span data-ttu-id="97c8d-103">Der Tokenanbieter, der als Bindungsparameter verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="97c8d-103">The token provider used as a binding parameter.</span></span></param>
        <summary><span data-ttu-id="97c8d-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="97c8d-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.AddBindingParameters (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Channels.BindingParameterCollection bindingParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Channels.BindingParameterCollection bindingParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)" />
      <MemberSignature Language="VB.NET" Value="Sub AddBindingParameters (endpoint As ServiceEndpoint, bindingParameters As BindingParameterCollection) Implements IEndpointBehavior.AddBindingParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="bindingParameters" Type="System.ServiceModel.Channels.BindingParameterCollection" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="97c8d-105">Der zu verändernde Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="97c8d-105">The endpoint to modify.</span></span></param>
        <param name="bindingParameters"><span data-ttu-id="97c8d-106">Die Objekte, die von Bindungselementen zur Unterstützung des Verhaltens benötigt werden.</span><span class="sxs-lookup"><span data-stu-id="97c8d-106">The objects that binding elements require to support the behavior.</span></span></param>
        <summary><span data-ttu-id="97c8d-107">Übergibt die angegebenen Daten zur Laufzeit für der angegebenen Bindung Service Bus-Anmeldeinformationen Verhalten zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="97c8d-107">Passes the specified data at runtime to the specified binding to support Service Bus credential behavior.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyClientBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.ClientRuntime clientRuntime);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.ClientRuntime clientRuntime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="clientRuntime" Type="System.ServiceModel.Dispatcher.ClientRuntime" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="97c8d-108">Der Endpunkt, der angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="97c8d-108">The endpoint that is to be customized.</span></span></param>
        <param name="clientRuntime"><span data-ttu-id="97c8d-109">Die Clientlaufzeit, die angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="97c8d-109">The client runtime to be customized.</span></span></param>
        <summary><span data-ttu-id="97c8d-110">Implementiert eine Änderung oder Erweiterung des Clients in einem Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="97c8d-110">Implements a modification or extension of the client across an endpoint.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyDispatchBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="endpointDispatcher" Type="System.ServiceModel.Dispatcher.EndpointDispatcher" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="97c8d-111">Der Endpunkt, der den Vertrag verfügbar macht.</span><span class="sxs-lookup"><span data-stu-id="97c8d-111">The endpoint that exposes the contract.</span></span></param>
        <param name="endpointDispatcher"><span data-ttu-id="97c8d-112">Der Endpunktverteiler, der geändert oder erweitert werden soll.</span><span class="sxs-lookup"><span data-stu-id="97c8d-112">The endpoint dispatcher to be modified or extended.</span></span></param>
        <summary><span data-ttu-id="97c8d-113">Implementiert eine Änderung oder eine Erweiterung des Diensts in einem Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="97c8d-113">Implements a modification or extension of the service across an endpoint.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.Validate">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.Validate (System.ServiceModel.Description.ServiceEndpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.Validate(class System.ServiceModel.Description.ServiceEndpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#Validate(System.ServiceModel.Description.ServiceEndpoint)" />
      <MemberSignature Language="VB.NET" Value="Sub Validate (endpoint As ServiceEndpoint) Implements IEndpointBehavior.Validate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.Validate(System.ServiceModel.Description.ServiceEndpoint)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="97c8d-114">Der zu überprüfende Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="97c8d-114">The endpoint to validate.</span></span></param>
        <summary><span data-ttu-id="97c8d-115">Bestätigt, dass der Endpunkt einen gültigen Windows Azure Service Bus-Endpunkt, der durch das Verhalten dieser Instanz geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="97c8d-115">Confirms that the endpoint is a valid Windows Azure Service Bus endpoint that can be modified by the behavior of this instance.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider with get, set" Usage="Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="97c8d-116">Ruft ab oder legt den Tokenanbieter, der als Bindungsparameter verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="97c8d-116">Gets or sets the token provider that is used as a binding parameter.</span></span></summary>
        <value><span data-ttu-id="97c8d-117">Der Tokenanbieter, der als Bindungsparameter verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="97c8d-117">The token provider used as a binding parameter.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>