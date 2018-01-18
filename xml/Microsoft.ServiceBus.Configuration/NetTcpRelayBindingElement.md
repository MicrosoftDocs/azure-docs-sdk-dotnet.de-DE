<Type Name="NetTcpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class NetTcpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetTcpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class NetTcpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="353a5-101">Ein Konfigurationselement, das eine sichere, zuverlässige Bindung, die geeignet ist, für die computerübergreifende Kommunikation über das Azure Service Bus-Relay beschreibt.</span><span class="sxs-lookup"><span data-stu-id="353a5-101">A configuration element that describes a secure, reliable binding suitable for cross-machine communication through the Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="353a5-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="353a5-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="353a5-103">Der Konfigurationsname der Bindung.</span><span class="sxs-lookup"><span data-stu-id="353a5-103">The binding configuration name.</span></span></param>
        <summary><span data-ttu-id="353a5-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />-Klasse mit einem angegebenen Konfigurationsnamen.</span><span class="sxs-lookup"><span data-stu-id="353a5-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> class with a specified configuration name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-105">Ruft den Typ dieses Konfigurationselements ab.</span><span class="sxs-lookup"><span data-stu-id="353a5-105">Gets the type of this configuration element.</span></span> <span data-ttu-id="353a5-106">(Überschreibt StandardBindingElement.BindingElementType.)</span><span class="sxs-lookup"><span data-stu-id="353a5-106">(Overrides StandardBindingElement.BindingElementType.)</span></span></summary>
        <value><span data-ttu-id="353a5-107">Gibt eine <see cref="T:System.Type" /> , den Konfigurationselementtyp enthält.</span><span class="sxs-lookup"><span data-stu-id="353a5-107">Returns a <see cref="T:System.Type" /> that contains the configuration element type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
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
        <summary><span data-ttu-id="353a5-108">Ruft ab oder legt den Verbindungsmodus in der Datei "App.config" für diese Konfiguration gespeichert.</span><span class="sxs-lookup"><span data-stu-id="353a5-108">Gets or sets the connection mode stored in the App.config file for this configuration.</span></span></summary>
        <value><span data-ttu-id="353a5-109">Gibt eine <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> , enthält den Verbindungsmodus der Standardwert wird mittels Relay weitergeleitet.</span><span class="sxs-lookup"><span data-stu-id="353a5-109">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> that contains the connection mode The default is Relayed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.InitializeFrom binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="353a5-110">Die Bindung nicht initialisieren.</span><span class="sxs-lookup"><span data-stu-id="353a5-110">The binding to initialize from.</span></span></param>
        <summary><span data-ttu-id="353a5-111">Initialisiert den Inhalt dieses Bindungskonfigurationselements aus den Eigenschaftswerten einer angegebenen Bindung.</span><span class="sxs-lookup"><span data-stu-id="353a5-111">Initializes the contents of this binding configuration element from the property values of a specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
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
        <summary><span data-ttu-id="353a5-112">Ruft ab oder legt fest, ob die RelayBindung dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="353a5-112">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="353a5-113">"true", wenn die RelayBindung dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="353a5-113">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
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
        <summary><span data-ttu-id="353a5-114">Ruft ab oder legt einen Wert fest, in der Datei "App.config", die die maximale Anzahl an Kanälen angibt, die akzeptiert werden auf dem Listener warten können.</span><span class="sxs-lookup"><span data-stu-id="353a5-114">Gets or sets a value in the App.config file that specifies the maximum number of channels that can wait to be accepted on the listener.</span></span></summary>
        <value><span data-ttu-id="353a5-115">Gibt die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="353a5-115">Returns the maximum number of queued connection requests that can be pending.</span></span> <span data-ttu-id="353a5-116">Der Standard ist 10.</span><span class="sxs-lookup"><span data-stu-id="353a5-116">The default is 10.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferPoolSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-117">Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Größe für einen Pufferpool enthält, die von der Bindung verarbeitet TCP-Nachrichten gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="353a5-117">Gets or sets a value from the App.config file that contains the maximum size for a buffer pool that stores TCP messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="353a5-118">Gibt zulässige die maximale Größe für einen Pufferpool, der von der Bindung verarbeitet Nachrichten gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="353a5-118">Returns the maximum size allowed for a buffer pool that stores messages processed by the binding.</span></span> <span data-ttu-id="353a5-119">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="353a5-119">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-120">Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Größe des Puffers zum Speichern von Nachrichten im Arbeitsspeicher in Bytes angibt.</span><span class="sxs-lookup"><span data-stu-id="353a5-120">Gets or sets a value from the App.config file that specifies the maximum size, in bytes, of the buffer used to store messages in memory.</span></span></summary>
        <value><span data-ttu-id="353a5-121">Die maximale Größe (in Byte) des Puffers, der verwendet wird, um Meldungen im Arbeitsspeicher zu speichern.</span><span class="sxs-lookup"><span data-stu-id="353a5-121">The maximum size, in bytes, of the buffer used to store messages in memory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-122">Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Anzahl ausgehender und eingehender Verbindungen angibt, der Dienst erstellt bzw. annimmt.</span><span class="sxs-lookup"><span data-stu-id="353a5-122">Gets or sets a value from the App.config file that specifies the maximum number of outbound and inbound connections the service creates and accepts respectively.</span></span></summary>
        <value><span data-ttu-id="353a5-123">Auf dem Client gibt die maximale Anzahl an Verbindungen, für die nachfolgende Wiederverwendung "zusammengelegt" werden; auf dem Server gibt Sie die maximale Anzahl zulässiger Verbindungen mit "Ausstehend" Verteilung zurück.</span><span class="sxs-lookup"><span data-stu-id="353a5-123">On the client, returns the maximum number of connections to be pooled for subsequent reuse; on the server, returns the maximum number of connections allowed to be pending dispatch.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxReceivedMessageSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-124">Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Größe einer Nachricht enthält, die in einem mit dieser Bindung konfigurierten Kanal empfangen werden können.</span><span class="sxs-lookup"><span data-stu-id="353a5-124">Gets or sets a value from the App.config file that contains the maximum size of a message that can be received on a channel configured with this binding.</span></span></summary>
        <value><span data-ttu-id="353a5-125">Gibt die maximale Größe in Byte für eine Nachricht, die von der Bindung verarbeitet wird zurück.</span><span class="sxs-lookup"><span data-stu-id="353a5-125">Returns maximum size, in bytes, for a message that is processed by the binding.</span></span> <span data-ttu-id="353a5-126">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="353a5-126">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.OnApplyConfiguration binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="353a5-127">Die Bindung, die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="353a5-127">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="353a5-128">Die Einstellungen dieses Konfigurationselements auf das angegebene Bindungselement angewendet.</span><span class="sxs-lookup"><span data-stu-id="353a5-128">Applies the settings of this configuration element to the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-129">Ruft eine ConfigurationPropertyCollection-Instanz, die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält.</span><span class="sxs-lookup"><span data-stu-id="353a5-129">Gets a ConfigurationPropertyCollection instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span> <span data-ttu-id="353a5-130">(Überschreibt StandardBindingElement.Properties.)</span><span class="sxs-lookup"><span data-stu-id="353a5-130">(Overrides StandardBindingElement.Properties.)</span></span></summary>
        <value><span data-ttu-id="353a5-131">Eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements.</span><span class="sxs-lookup"><span data-stu-id="353a5-131">A collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("readerQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-132">Ruft einen Wert aus der Datei "App.config", die Beschränkungen der Komplexität von SOAP-Nachrichten setzt, die von mit dieser Bindung konfigurierten Endpunkten verarbeitet werden können.</span><span class="sxs-lookup"><span data-stu-id="353a5-132">Gets a value from the App.config file that puts constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="353a5-133">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> , das die komplexitätseinschränkungen für ausgetauschte SOAP-Nachrichten angibt.</span><span class="sxs-lookup"><span data-stu-id="353a5-133">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that specifies the complexity constraints on SOAP messages exchanged.</span></span> <span data-ttu-id="353a5-134">Die Standardwerte für diese Einschränkungen werden im folgenden Hinweisabschnitt angegeben.</span><span class="sxs-lookup"><span data-stu-id="353a5-134">The default values for these constraints are provided in the following Remarks section.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As StandardBindingOptionalReliableSessionElement" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("reliableSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-135">Ruft ein Konfigurationselement ab, das angibt, ob zuverlässige Sitzungen zwischen Kanalendpunkten erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="353a5-135">Gets a configuration element that specifies whether reliable sessions are established between channel endpoints.</span></span></summary>
        <value><span data-ttu-id="353a5-136">Gibt eine <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> , der angibt, ob eine zuverlässige WS-RM-Sitzung zwischen kanalendpunkten eingerichtet wird.</span><span class="sxs-lookup"><span data-stu-id="353a5-136">Returns a <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> that indicates whether a WS-RM reliable session is established between channel endpoints.</span></span> <span data-ttu-id="353a5-137">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="353a5-137">The default value is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetTcpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-138">Ruft einen Wert aus der Datei "App.config", die bestimmt, der den Sicherheitstyp mit dieser Bindung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="353a5-138">Gets a value from the App.config file that determines the type of security to be used with this binding.</span></span></summary>
        <value><span data-ttu-id="353a5-139">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> , das die Sicherheitseinstellungen für die zugeordnete Bindung enthält.</span><span class="sxs-lookup"><span data-stu-id="353a5-139">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> that contains the security settings for the associated binding.</span></span> <span data-ttu-id="353a5-140">Der Standardwert ist none. Die <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> abrufen aus der zugehörigen Bindung wird indirekt erstellt, mit einem NetTcpRelayBinding.</span><span class="sxs-lookup"><span data-stu-id="353a5-140">The default value is none.The <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> you retrieve from the associated binding is created indirectly with a NetTcpRelayBinding.</span></span> <span data-ttu-id="353a5-141">Daher nach der Erstellung der Bindungsnamens können nicht Sie dieses Objekt durch ein neues Objekt ersetzen, wenn Sie auch eine neue Bindung erstellen.</span><span class="sxs-lookup"><span data-stu-id="353a5-141">As such, after the binding is created, you cannot replace this object with a new object unless you also create a new binding.</span></span> <span data-ttu-id="353a5-142">Allerdings können viele Elemente der WebHttpRelaySecurity über Sicherheitseigenschaft festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="353a5-142">However, many members of WebHttpRelaySecurity can be set through security property.</span></span> <span data-ttu-id="353a5-143">Weitere Informationen zur bindungssicherheit finden Sie unter im Abschnitt Sicherheit und Schutz.</span><span class="sxs-lookup"><span data-stu-id="353a5-143">For more information on binding security, see the Security and Protection section.</span></span> <span data-ttu-id="353a5-144">Zusammen mit dem Typ von Transport und Codierung stellen die Sicherheitseinstellungen für eine der drei wichtigsten Eigenschaften, die dieser Bindung zu definieren.</span><span class="sxs-lookup"><span data-stu-id="353a5-144">Along with the type of transport and encoding, the Security settings represent one of the three main properties that define this binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transferMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="353a5-145">Ruft ab oder legt einen Wert aus der Datei "App.config", der angibt, ob Nachrichten gepuffert oder gestreamt werden oder eine Anforderung oder Antwort.</span><span class="sxs-lookup"><span data-stu-id="353a5-145">Gets or sets a value from the App.config file that specifies whether messages are buffered or streamed or a request or response.</span></span></summary>
        <value><span data-ttu-id="353a5-146">Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> enthält, die angibt, ob der Dienst mit der Bindung verwendet Streaming- oder Puffermodus (oder beides) nachrichtenübertragung.</span><span class="sxs-lookup"><span data-stu-id="353a5-146">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span> <span data-ttu-id="353a5-147">Die möglichen Werte sind wie folgt: BufferedStreamedStreamedRequestStreamedResponseThe-Standardwert ist Buffered.Specifying <see cref="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" /> auf Streamed bedeutet StreamedRequest und StreamedResponse.</span><span class="sxs-lookup"><span data-stu-id="353a5-147">The possible values are as follows: BufferedStreamedStreamedRequestStreamedResponseThe default value is Buffered.Specifying <see cref="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" /> to Streamed implies both StreamedRequest and StreamedResponse.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>