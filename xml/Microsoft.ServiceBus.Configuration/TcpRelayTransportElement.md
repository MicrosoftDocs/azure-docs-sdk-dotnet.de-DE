<Type Name="TcpRelayTransportElement" FullName="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement">
  <TypeSignature Language="C#" Value="public sealed class TcpRelayTransportElement : Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TcpRelayTransportElement extends Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TcpRelayTransportElement&#xA;Inherits ConnectionOrientedTransportElement" />
  <TypeSignature Language="F#" Value="type TcpRelayTransportElement = class&#xA;    inherit ConnectionOrientedTransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="3e65b-101">Gibt ein Konfigurationselement an, das dafür sorgt, dass ein Kanal Meldungen auf dem TCP-Transport überträgt, wenn er in einer benutzerdefinierten Bindung eingeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3e65b-101">Specifies a configuration element that causes a channel to transfer messages on the TCP transport when it is included in a custom binding.</span></span> <span data-ttu-id="3e65b-102">Diese Klasse kann nicht vererbt werden.</span><span class="sxs-lookup"><span data-stu-id="3e65b-102">This class cannot be inherited.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="3e65b-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e65b-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="tcpRelayTransportElement.ApplyConfiguration bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement"> <span data-ttu-id="3e65b-104">Das Bindungselement, das die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="3e65b-104">The binding element to update the settings of.</span></span></param>
        <summary><span data-ttu-id="3e65b-105">Die Einstellungen dieses Konfigurationselements auf das angegebene Bindungselement angewendet.</span><span class="sxs-lookup"><span data-stu-id="3e65b-105">Applies the settings of this configuration element to the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e65b-106">Ruft den Typ dieses Bindungselements ab.</span><span class="sxs-lookup"><span data-stu-id="3e65b-106">Gets the type of this binding element.</span></span></summary>
        <value><span data-ttu-id="3e65b-107">Gibt eine <see cref="T:System.Type" /> , die einen Bindung Elementtyp enthält.</span><span class="sxs-lookup"><span data-stu-id="3e65b-107">Returns a <see cref="T:System.Type" /> containing a binding element type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e65b-108">Ruft ab oder legt den Verbindungsmodus in der Datei "App.config" für diese Konfiguration gespeichert.</span><span class="sxs-lookup"><span data-stu-id="3e65b-108">Gets or sets the connection mode stored in the App.config file for this configuration.</span></span></summary>
        <value><span data-ttu-id="3e65b-109">Gibt eine <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> , die den Verbindungsmodus enthält.</span><span class="sxs-lookup"><span data-stu-id="3e65b-109">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> that contains the connection mode.</span></span> <span data-ttu-id="3e65b-110">Die Standardeinstellung ist mittels Relay weitergeleitet.</span><span class="sxs-lookup"><span data-stu-id="3e65b-110">The default setting is Relayed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionPoolSettings As SocketConnectionPoolSettingsElement" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionPoolSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e65b-111">Ruft ab oder legt einen XML-Wert, der die verbindungspooleinstellungen für die aktuelle Instanz beschreibt.</span><span class="sxs-lookup"><span data-stu-id="3e65b-111">Gets or sets an XML value that describes the connection pool settings for the current instance.</span></span></summary>
        <value><span data-ttu-id="3e65b-112">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" /> , enthält die verbindungspooleinstellungen, das verwendet wird, durch das Bindungselement, das auf die aktuelle Instanz angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="3e65b-112">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" /> that contains the connection pool settings used by the binding element that the current instance is applied to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="tcpRelayTransportElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"> <span data-ttu-id="3e65b-113">Die Konfigurationselemente kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="3e65b-113">The configuration elements to be copied.</span></span></param>
        <summary><span data-ttu-id="3e65b-114">Kopiert den Inhalt des angegebenen Konfigurationselements in dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="3e65b-114">Copies the content of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="tcpRelayTransportElement.CreateDefaultBindingElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.TransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="3e65b-115">Erstellt ein Bindungselement aus den Einstellungen in diesem Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="3e65b-115">Creates a binding element from the settings in this configuration element.</span></span></summary>
        <returns><span data-ttu-id="3e65b-116">Gibt eine <see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> , enthält das standardbindungselement.</span><span class="sxs-lookup"><span data-stu-id="3e65b-116">Returns a <see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> that contains the default binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.InitializeFrom(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="tcpRelayTransportElement.InitializeFrom bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement"><span data-ttu-id="3e65b-117">Das Bindungselement aus initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="3e65b-117">The binding element to initialize from.</span></span></param>
        <summary><span data-ttu-id="3e65b-118">Initialisiert dieses Bindungskonfigurationselement mit dem Inhalt des angegebenen Bindungselements.</span><span class="sxs-lookup"><span data-stu-id="3e65b-118">Initializes this binding configuration element with the content of the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("isDynamic", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e65b-119">Ruft ab oder legt fest, ob die RelayBindung dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="3e65b-119">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="3e65b-120">"true", wenn die RelayBindung dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="3e65b-120">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("listenBacklog", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e65b-121">Ruft ab oder legt einen XML-Wert, der die maximale Anzahl der ausstehenden verbindungsanforderungen in der Warteschlange enthält.</span><span class="sxs-lookup"><span data-stu-id="3e65b-121">Gets or sets an XML value containing the maximum number of queued connection requests that can be pending.</span></span></summary>
        <value><span data-ttu-id="3e65b-122">Gibt die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="3e65b-122">Returns the maximum number of queued connection requests that can be pending.</span></span> <span data-ttu-id="3e65b-123">Der Standard ist 10.</span><span class="sxs-lookup"><span data-stu-id="3e65b-123">The default is 10.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e65b-124">Ruft die Auflistung von Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="3e65b-124">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("relayClientAuthenticationType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e65b-125">Ruft ab oder legt einen XML-Wert, der die relayclient-Authentifizierungstyp enthält.</span><span class="sxs-lookup"><span data-stu-id="3e65b-125">Gets or sets an XML value that contains the relay client authentication type.</span></span></summary>
        <value><span data-ttu-id="3e65b-126">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält die relayclient-Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="3e65b-126">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the relay client authentication type.</span></span> <span data-ttu-id="3e65b-127">Der Standardwert ist RelayClientAuthenticationType.RelayAccessToken.</span><span class="sxs-lookup"><span data-stu-id="3e65b-127">The default is RelayClientAuthenticationType.RelayAccessToken.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>