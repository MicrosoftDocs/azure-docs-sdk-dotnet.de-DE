<Type Name="RelayedOnewayTransportBindingElement" FullName="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement">
  <TypeSignature Language="C#" Value="public class RelayedOnewayTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement, System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayedOnewayTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement implements class System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayedOnewayTransportBindingElement&#xA;Inherits TransportBindingElement&#xA;Implements IPolicyExportExtension" />
  <TypeSignature Language="F#" Value="type RelayedOnewayTransportBindingElement = class&#xA;    inherit TransportBindingElement&#xA;    interface IPolicyExportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="045cf-101">Stellt das Transportbindungselement, die für die unidirektionale Kommunikation verwendet.</span><span class="sxs-lookup"><span data-stu-id="045cf-101">Represents the transport binding element used for one-way communication.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="045cf-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="045cf-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" Usage="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement relayClientAuthenticationType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType"><span data-ttu-id="045cf-103">Die relayclient-Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="045cf-103">The relay client authentication type.</span></span> <span data-ttu-id="045cf-104">Dabei kann es sich um <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" /> oder <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />.</span><span class="sxs-lookup"><span data-stu-id="045cf-104">This can be either <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" /> or <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />.</span></span></param>
        <summary><span data-ttu-id="045cf-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> -Klasse mit den angegebenen Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="045cf-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> class, using the specified authentication type.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement (Microsoft.ServiceBus.RelayedOnewayTransportBindingElement elementToClone);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement elementToClone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayedOnewayTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (elementToClone As RelayedOnewayTransportBindingElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement -&gt; Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" Usage="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement elementToClone" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementToClone" Type="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="elementToClone"><span data-ttu-id="045cf-106">Das Element, das Klonen.</span><span class="sxs-lookup"><span data-stu-id="045cf-106">The element to clone.</span></span></param>
        <summary><span data-ttu-id="045cf-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> -Klasse unter Verwendung des angegebenen Elements.</span><span class="sxs-lookup"><span data-stu-id="045cf-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> class, using the specified element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, Microsoft.ServiceBus.RelayedOnewayConnectionMode connectionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode connectionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType,Microsoft.ServiceBus.RelayedOnewayConnectionMode)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType * Microsoft.ServiceBus.RelayedOnewayConnectionMode -&gt; Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" Usage="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement (relayClientAuthenticationType, connectionMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
        <Parameter Name="connectionMode" Type="Microsoft.ServiceBus.RelayedOnewayConnectionMode" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType"><span data-ttu-id="045cf-108">Die relayclient-Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="045cf-108">The relay client authentication type.</span></span> <span data-ttu-id="045cf-109">Dabei kann es sich um <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" /> oder <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />.</span><span class="sxs-lookup"><span data-stu-id="045cf-109">This can be either <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" /> or <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />.</span></span></param>
        <param name="connectionMode"><span data-ttu-id="045cf-110">der Verbindungsmodus.</span><span class="sxs-lookup"><span data-stu-id="045cf-110">The connection mode.</span></span> <span data-ttu-id="045cf-111">Dabei kann es sich um <see cref="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Unicast" /> oder <see cref="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Multicast" />.</span><span class="sxs-lookup"><span data-stu-id="045cf-111">This can be either <see cref="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Unicast" /> or <see cref="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Multicast" />.</span></span></param>
        <summary><span data-ttu-id="045cf-112">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> -Klasse unter Verwendung der angegebenen Typ und Authentifizierungsmodus.</span><span class="sxs-lookup"><span data-stu-id="045cf-112">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> class, using the specified authentication type and connection mode.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="relayedOnewayTransportBindingElement.BuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="045cf-113">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="045cf-113">The binding context that provides context for the binding element.</span></span></param>
        <summary><span data-ttu-id="045cf-114">Erstellt eine Kanalfactory erstellt, für die Erstellung von Kanälen des angegebenen Typs und, die aus dem angegebenen Bindungskontext initialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-114">Creates a channel factory for creating channels of the specified type and that is initialized from the specified binding context.</span></span></summary>
        <returns><span data-ttu-id="045cf-115">Eine Kanalfactory für Kanäle des angegebenen Typs und, erstellen, wird aus dem angegebenen Bindungskontext initialisiert.</span><span class="sxs-lookup"><span data-stu-id="045cf-115">A channel factory for creating channels of the specified type and that is initialized from the specified binding context.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="relayedOnewayTransportBindingElement.BuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>System.ServiceModel.Channels.IChannel</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="045cf-116">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="045cf-116">The binding context that provides context for the binding element.</span></span></param>
        <summary><span data-ttu-id="045cf-117">Erstellt einen Kanallistener, der Kanäle des angegebenen Typs akzeptiert und, initialisiert, aus dem angegebenen Bindungskontext.</span><span class="sxs-lookup"><span data-stu-id="045cf-117">Creates a channel listener that accepts channels of the specified type and that is initialized from the specified binding context.</span></span></summary>
        <returns><span data-ttu-id="045cf-118">Ein Kanallistener, der Kanäle des angegebenen Typs akzeptiert und, die aus dem angegebenen Bindungskontext initialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-118">A channel listener that accepts channels of the specified type and that is initialized from the specified binding context.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of TChannel) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="relayedOnewayTransportBindingElement.CanBuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="045cf-119">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="045cf-119">The binding context that provides context for this binding element.</span></span></param>
        <summary><span data-ttu-id="045cf-120">Gibt einen Wert, der angibt, ob das Bindungselement eine Kanalfactory des angegebenen Typs erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="045cf-120">Returns a value that indicates whether this binding element can build a channel factory of the specified type.</span></span></summary>
        <returns><span data-ttu-id="045cf-121">"true", wenn eine Kanalfactory erstellt werden kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="045cf-121">true if a channel factory can be built; otherwise false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="relayedOnewayTransportBindingElement.CanBuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>System.ServiceModel.Channels.IChannel</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="045cf-122">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="045cf-122">The binding context that provides context for this binding element.</span></span></param>
        <summary><span data-ttu-id="045cf-123">Gibt einen Wert, der angibt, ob das Bindungselement, das einen Kanallistener für den angegebenen Typ von Kanal erstellen kann.</span><span class="sxs-lookup"><span data-stu-id="045cf-123">Returns a value that indicates whether the binding element can build a channel listener for the specified type of channel.</span></span></summary>
        <returns><span data-ttu-id="045cf-124">"true", wenn ein Kanallistener für den angegebenen Kanaltyp erstellt werden kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="045cf-124">true if a channel listener can be built for the specified type of channel; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-125">Ruft ab oder legt die maximale Zeit, die ein Kanal in den Initialisierungsstatus befinden kann, bevor Sie unterbrochen wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-125">Gets or sets the maximum time a channel can be in the initialization status before being disconnected.</span></span></summary>
        <value><span data-ttu-id="045cf-126">Die maximale Zeit, die ein Kanal in den Initialisierungsstatus befinden kann, bevor Sie unterbrochen wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-126">The maximum time a channel can be in the initialization status before being disconnected.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="relayedOnewayTransportBindingElement.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="045cf-127">Gibt eine Kopie dieser Instanz von der <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> Binding-Element.</span><span class="sxs-lookup"><span data-stu-id="045cf-127">Returns a copy of this instance of the <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> binding element.</span></span></summary>
        <returns><span data-ttu-id="045cf-128">Ein Bindungselement, das einen tiefen Klon dieses Bindungselements enthält.</span><span class="sxs-lookup"><span data-stu-id="045cf-128">A binding element that contains a deep clone of this binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-129">Ruft die Puffergröße ab oder legt die Puffergröße fest, die zum Übertragen eines Teils der Meldung vom Client oder Dienst verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-129">Gets or sets the size of the buffer used to transmit a part of the serialized message on the wire from the client or service.</span></span></summary>
        <value><span data-ttu-id="045cf-130">Die Puffergröße, die zum Übertragen eines Teils der Meldung vom Client oder Dienst verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-130">The size of the buffer used to transmit a part of the serialized message on the wire from the client or service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayedOnewayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As RelayedOnewayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.RelayedOnewayConnectionMode with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-131">Ruft den Verbindungsmodus in dieses Bindungselement verwendet.</span><span class="sxs-lookup"><span data-stu-id="045cf-131">Gets the connection mode used in this binding element.</span></span> <span data-ttu-id="045cf-132">Der Verbindungsmodus möglich die <see cref="T:Microsoft.ServiceBus.RelayedOnewayConnectionMode" /> Enumerationswerte.</span><span class="sxs-lookup"><span data-stu-id="045cf-132">The connection mode can be one of the <see cref="T:Microsoft.ServiceBus.RelayedOnewayConnectionMode" /> enumeration values.</span></span></summary>
        <value><span data-ttu-id="045cf-133">Der Verbindungsmodus in dieses Bindungselement verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-133">The connection mode used in this binding element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPoolSettings As SocketConnectionPoolSettings" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.SocketConnectionPoolSettings" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketConnectionPoolSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-134">Ruft die Verbindung-Einstellungen für die aktuelle Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="045cf-134">Gets the connection pool settings for the current instance.</span></span></summary>
        <value><span data-ttu-id="045cf-135">Die verbindungspooleinstellungen für die aktuelle Instanz.</span><span class="sxs-lookup"><span data-stu-id="045cf-135">The connection pool settings for the current instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="relayedOnewayTransportBindingElement.GetProperty context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="045cf-136">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="045cf-136">The binding context that provides context for this binding element.</span></span></param>
        <summary><span data-ttu-id="045cf-137">Ein Objekt des angeforderten Typs, sofern vorhanden, von der entsprechenden Ebene im bindungsstapel zurück.</span><span class="sxs-lookup"><span data-stu-id="045cf-137">Returns an object of the requested type, if present, from the appropriate layer in the binding stack.</span></span></summary>
        <returns><span data-ttu-id="045cf-138">Das Objekt des angeforderten Typs Wenn gefunden; Andernfalls wird null zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="045cf-138">The object of the requested type if found; otherwise, returns null.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="045cf-139">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Hostname zum Erreichen des Diensts bei übereinstimmendem URI verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="045cf-139">Gets or sets a value that indicates whether the hostname is used to reach the service when matching the URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-140">Ruft die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange ab, oder legt diese fest.</span><span class="sxs-lookup"><span data-stu-id="045cf-140">Gets or sets the maximum number of queued connection requests that can be pending.</span></span></summary>
        <value><span data-ttu-id="045cf-141">Die maximale Anzahl der in der Warteschlange Verbindung.</span><span class="sxs-lookup"><span data-stu-id="045cf-141">The maximum number of queued connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-142">Ruft ab oder legt die maximale Größe in Byte des Puffers, der eingehende Nachrichten enthält, die von dieser Bindung verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="045cf-142">Gets or sets the maximum size in bytes of the buffer that holds incoming messages that are processed by this binding.</span></span></summary>
        <value><span data-ttu-id="045cf-143">Die maximale Größe in Byte des Puffers, der eingehende Nachrichten enthält, die von dieser Bindung verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="045cf-143">The maximum size in bytes of the buffer that holds incoming messages that are processed by this binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-144">Ruft ab oder legt das maximale Zeitintervall fest, eine Nachricht oder einen Teil einer Nachricht im Arbeitsspeicher gepuffert bleiben kann, bevor Sie versendet wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-144">Gets or sets the maximum interval of time that a message or a portion of a message can remain buffered in memory before being sent out.</span></span></summary>
        <value><span data-ttu-id="045cf-145">Das maximale Zeitintervall, die verbleiben kann, eine Nachricht oder einen Teil einer Nachricht im Arbeitsspeicher gepuffert werden, bevor Sie versendet wird.</span><span class="sxs-lookup"><span data-stu-id="045cf-145">The maximum interval of time that a message or a portion of a message can remain buffered in memory before being sent out.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-146">Ruft die maximale Anzahl ausstehender asynchroner Annahmethreads ab, die für die Verarbeitung eingehender Verbindungen beim Dienst zur Verfügung stehen, oder legt die maximale Anzahl fest.</span><span class="sxs-lookup"><span data-stu-id="045cf-146">Gets or sets the maximum number of pending asynchronous accept threads that are available for processing incoming connections on the service.</span></span></summary>
        <value><span data-ttu-id="045cf-147">Die maximale Anzahl ausstehender asynchroner Annahmethreads, die für die Verarbeitung eingehender Verbindungen beim Dienst zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="045cf-147">The maximum number of pending asynchronous accept threads that are available for processing incoming connections on the service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-148">Ruft die maximale Anzahl ausstehender Verbindungen ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="045cf-148">Gets or sets the maximum number of pending connections.</span></span></summary>
        <value><span data-ttu-id="045cf-149">Die maximale Anzahl ausstehender Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="045cf-149">The maximum number of pending connections.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-150">Ruft ab oder legt den Typ der Azure Access Control-Authentifizierung, die von diesem Bindungselement verwendet.</span><span class="sxs-lookup"><span data-stu-id="045cf-150">Gets or sets the type of Azure Access Control authentication used by this binding element.</span></span></summary>
        <value><span data-ttu-id="045cf-151">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , die den Typ der Authentifizierung verwendet, die von diesem Bindungselement darstellt. Der Standardwert ist <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />.</span><span class="sxs-lookup"><span data-stu-id="045cf-151">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that represents the type of authentication used by this binding element.The default value is <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="045cf-152">Ruft das URI-Schema, das von diesem Bindungselement verwendet.</span><span class="sxs-lookup"><span data-stu-id="045cf-152">Gets the URI scheme used by this binding element.</span></span></summary>
        <value><span data-ttu-id="045cf-153">Das URI-Schema, das von diesem Bindungselement verwendet.</span><span class="sxs-lookup"><span data-stu-id="045cf-153">The URI scheme used by this binding element.</span></span> <span data-ttu-id="045cf-154">Der zurückgegebene Wert ist "Sb".</span><span class="sxs-lookup"><span data-stu-id="045cf-154">The value returned is “sb”.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportPolicy (exporter As MetadataExporter, context As PolicyConversionContext) Implements IPolicyExportExtension.ExportPolicy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.MetadataExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.PolicyConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter"><span data-ttu-id="045cf-155">Die MetadataExporter, die Sie zum Ändern des Exportprozesses verwenden können.</span><span class="sxs-lookup"><span data-stu-id="045cf-155">The MetadataExporter that you can use to modify the exporting process.</span></span></param>
        <param name="context"><span data-ttu-id="045cf-156">Die PolicyConversionContext, die Sie zum Einfügen einer benutzerdefinierten Richtlinienassertion verwenden können.</span><span class="sxs-lookup"><span data-stu-id="045cf-156">The PolicyConversionContext that you can use to insert your custom policy assertion.</span></span></param>
        <summary>
            <span data-ttu-id="045cf-157">Exportiert eine benutzerdefinierte Richtlinienassertion über diese Bindung an.</span><span class="sxs-lookup"><span data-stu-id="045cf-157">Exports a custom policy assertion about this binding.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>