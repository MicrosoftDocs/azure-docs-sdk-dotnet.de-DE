<Type Name="ServiceRegistrySettings" FullName="Microsoft.ServiceBus.ServiceRegistrySettings">
  <TypeSignature Language="C#" Value="public class ServiceRegistrySettings : System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRegistrySettings extends System.Object implements class System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceRegistrySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRegistrySettings&#xA;Implements IEndpointBehavior" />
  <TypeSignature Language="F#" Value="type ServiceRegistrySettings = class&#xA;    interface IEndpointBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
    <summary><span data-ttu-id="ce01e-101">Enthält die Einstellungen für die Azure Service Bus-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="ce01e-101">Contains the settings for the Azure Service Bus registry.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRegistrySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="ce01e-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ce01e-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRegistrySettings (Microsoft.ServiceBus.DiscoveryType discoveryType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.DiscoveryType discoveryType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.#ctor(Microsoft.ServiceBus.DiscoveryType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.ServiceRegistrySettings : Microsoft.ServiceBus.DiscoveryType -&gt; Microsoft.ServiceBus.ServiceRegistrySettings" Usage="new Microsoft.ServiceBus.ServiceRegistrySettings discoveryType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="discoveryType" Type="Microsoft.ServiceBus.DiscoveryType" />
      </Parameters>
      <Docs>
        <param name="discoveryType"><span data-ttu-id="ce01e-103">Der Discovery-Typ, der angibt, ob der Endpunkt öffentlich oder privat ist.</span><span class="sxs-lookup"><span data-stu-id="ce01e-103">The discovery type that indicates whether the endpoint is public or private.</span></span> </param>
        <summary><span data-ttu-id="ce01e-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" /> -Klasse unter Verwendung der angegebenen Ermittlungstyp.</span><span class="sxs-lookup"><span data-stu-id="ce01e-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" /> class using the specified discovery type.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="allowUnauthenticatedAccess">
      <MemberSignature Language="C#" Value="protected bool allowUnauthenticatedAccess;" />
      <MemberSignature Language="ILAsm" Value=".field family bool allowUnauthenticatedAccess" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceRegistrySettings.allowUnauthenticatedAccess" />
      <MemberSignature Language="VB.NET" Value="Protected allowUnauthenticatedAccess As Boolean " />
      <MemberSignature Language="F#" Value="val mutable allowUnauthenticatedAccess : bool" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.allowUnauthenticatedAccess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce01e-105">"true", wenn der Endpunkt für nicht authentifizierte Zugriffe zulässt; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="ce01e-105">true if the endpoint allows for unauthenticated access; otherwise, false.</span></span> <span data-ttu-id="ce01e-106">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="ce01e-106">The default value is false.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiscoveryMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.DiscoveryType DiscoveryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.DiscoveryType DiscoveryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceRegistrySettings.DiscoveryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property DiscoveryMode As DiscoveryType" />
      <MemberSignature Language="F#" Value="member this.DiscoveryMode : Microsoft.ServiceBus.DiscoveryType with get, set" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.DiscoveryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.DiscoveryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce01e-107">Ruft ab oder legt sie fest, wie der Dienst ermittelt werden kann.</span><span class="sxs-lookup"><span data-stu-id="ce01e-107">Gets or sets how the service is discovered.</span></span> </summary>
        <value><span data-ttu-id="ce01e-108">Gibt <see cref="T:Microsoft.ServiceBus.DiscoveryType" />. DiscoveryType.Public für die Ermittlung öffentlich sein; DiscoveryType.Private für die Ermittlung auf privat sein.</span><span class="sxs-lookup"><span data-stu-id="ce01e-108">Returns <see cref="T:Microsoft.ServiceBus.DiscoveryType" />.DiscoveryType.Public for discovery to be public; DiscoveryType.Private for discovery to be private.</span></span> <span data-ttu-id="ce01e-109">Der Standardwert ist DiscoveryType.Private.</span><span class="sxs-lookup"><span data-stu-id="ce01e-109">The default value is DiscoveryType.Private.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceRegistrySettings.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce01e-110">Ruft ab oder legt den Anzeigenamen für den Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="ce01e-110">Gets or sets the display name for the endpoint.</span></span></summary>
        <value><span data-ttu-id="ce01e-111">Gibt <see cref="T:System.String" />. Enthält den Anzeigenamen an.</span><span class="sxs-lookup"><span data-stu-id="ce01e-111">Returns <see cref="T:System.String" />.Contains the display name.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.AddBindingParameters (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Channels.BindingParameterCollection bindingParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Channels.BindingParameterCollection bindingParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="bindingParameters" Type="System.ServiceModel.Channels.BindingParameterCollection" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="ce01e-112">Der zu verändernde Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="ce01e-112">The endpoint to modify.</span></span></param>
        <param name="bindingParameters"><span data-ttu-id="ce01e-113">Die Objekte, die von Bindungselementen zur Unterstützung des Verhaltens benötigt werden.</span><span class="sxs-lookup"><span data-stu-id="ce01e-113">The objects that binding elements require to support the behavior.</span></span></param>
        <summary>
            <span data-ttu-id="ce01e-114">Übergibt Daten zur Laufzeit an Bindungen benutzerdefiniertes Verhalten unterstützen.</span><span class="sxs-lookup"><span data-stu-id="ce01e-114">Passes data at runtime to bindings to support custom behavior.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyClientBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.ClientRuntime clientRuntime);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.ClientRuntime clientRuntime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="clientRuntime" Type="System.ServiceModel.Dispatcher.ClientRuntime" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="ce01e-115">Der Endpunkt, der angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce01e-115">The endpoint that is to be customized.</span></span></param>
        <param name="clientRuntime"><span data-ttu-id="ce01e-116">Die Clientlaufzeit, die angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce01e-116">The client runtime to be customized.</span></span></param>
        <summary>
            <span data-ttu-id="ce01e-117">Diese Implementierung wird keine Aktion ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ce01e-117">This implementation does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyDispatchBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="endpointDispatcher" Type="System.ServiceModel.Dispatcher.EndpointDispatcher" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="ce01e-118">Der Endpunkt, der angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce01e-118">The endpoint that is to be customized.</span></span></param>
        <param name="endpointDispatcher"><span data-ttu-id="ce01e-119">Der Endpunktverteiler, der geändert oder erweitert werden soll.</span><span class="sxs-lookup"><span data-stu-id="ce01e-119">The endpoint dispatcher to be modified or extended.</span></span></param>
        <summary>
            <span data-ttu-id="ce01e-120">Diese Implementierung wird keine Aktion ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ce01e-120">This implementation does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.Validate">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.Validate (System.ServiceModel.Description.ServiceEndpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.Validate(class System.ServiceModel.Description.ServiceEndpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#Validate(System.ServiceModel.Description.ServiceEndpoint)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="ce01e-121">Der Endpunkt dieses Verhalten gilt.</span><span class="sxs-lookup"><span data-stu-id="ce01e-121">The endpoint this behavior applies to.</span></span></param>
        <summary>
            <span data-ttu-id="ce01e-122">Diese Methode hat keine Funktion.</span><span class="sxs-lookup"><span data-stu-id="ce01e-122">This method does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="transportProtectionEnabled">
      <MemberSignature Language="C#" Value="protected bool transportProtectionEnabled;" />
      <MemberSignature Language="ILAsm" Value=".field family bool transportProtectionEnabled" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceRegistrySettings.transportProtectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected transportProtectionEnabled As Boolean " />
      <MemberSignature Language="F#" Value="val mutable transportProtectionEnabled : bool" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.transportProtectionEnabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ce01e-123">"true", wenn der transportschutz aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="ce01e-123">true if transport protection is enabled; otherwise, false.</span></span> <span data-ttu-id="ce01e-124">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="ce01e-124">The default value is true.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>