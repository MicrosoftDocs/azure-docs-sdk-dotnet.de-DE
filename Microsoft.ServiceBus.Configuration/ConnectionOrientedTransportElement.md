<Type Name="ConnectionOrientedTransportElement" FullName="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement">
  <TypeSignature Language="C#" Value="public abstract class ConnectionOrientedTransportElement : System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConnectionOrientedTransportElement extends System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConnectionOrientedTransportElement&#xA;Inherits TransportElement" />
  <TypeSignature Language="F#" Value="type ConnectionOrientedTransportElement = class&#xA;    inherit TransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.TransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="8245b-101">Stellt das Konfigurationselement dar, das verbindungsorientierten Transportbindungselementen, wie beispielsweise TCP und Named Pipes, zusätzliche Konfigurationseinstellungen bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="8245b-101">Represents the configuration element that provides additional configuration settings to connection-oriented transport binding elements, such as TCP and named pipes.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="connectionOrientedTransportElement.ApplyConfiguration bindingElement" />
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
        <param name="bindingElement"><span data-ttu-id="8245b-102">Das Bindungselement, das die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="8245b-102">The binding element to update the settings of.</span></span></param>
        <summary><span data-ttu-id="8245b-103">Wendet die Einstellungen dieses Konfigurationselements auf das angegebene <see cref="T:System.ServiceModel.Channels.BindingElement" /> an.</span><span class="sxs-lookup"><span data-stu-id="8245b-103">Applies the settings of this configuration element to the specified <see cref="T:System.ServiceModel.Channels.BindingElement" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.TimeSpanOrInfiniteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("channelInitializationTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8245b-104">Ruft die maximale Zeit ab oder legt die maximale Zeit fest, in der sich der Kanal im Initialisierungsstatus befinden kann, bevor die Verbindung getrennt wird.</span><span class="sxs-lookup"><span data-stu-id="8245b-104">Gets or sets the maximum time the channel can be in the initialization status before being disconnected.</span></span></summary>
        <value><span data-ttu-id="8245b-105">Die maximale Zeit, die der Kanal in den Initialisierungsstatus befinden kann, bevor Sie unterbrochen wird.</span><span class="sxs-lookup"><span data-stu-id="8245b-105">The maximum time the channel can be in the initialization status before being disconnected.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8245b-106">Ruft die Puffergröße ab oder legt die Puffergröße fest, die zum Übertragen eines Teils der Meldung vom Client oder Dienst verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="8245b-106">Gets or sets the size of the buffer used to transmit a part of the serialized message on the wire from the client or service.</span></span></summary>
        <value><span data-ttu-id="8245b-107">Gibt eine <see cref="T:System.Int32" /> , enthält die Größe des Puffers zum Übertragen eines Teils der serialisierten Nachricht über das Netzwerk vom Client oder Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="8245b-107">Returns a <see cref="T:System.Int32" /> that contains the size of the buffer used to transmit a part of the serialized message on the wire from the client or service.</span></span> <span data-ttu-id="8245b-108">Der Standardwert ist 8 KB.</span><span class="sxs-lookup"><span data-stu-id="8245b-108">The default value is 8K.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="connectionOrientedTransportElement.CopyFrom from" />
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
        <param name="from"><span data-ttu-id="8245b-109">Das zu kopierende Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="8245b-109">The configuration element to be copied.</span></span></param>
        <summary><span data-ttu-id="8245b-110">Kopiert den Inhalt des angegebenen Konfigurationselements in dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="8245b-110">Copies the content of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("hostNameComparisonMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8245b-111">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Hostname zum Erreichen des Diensts bei übereinstimmendem URI verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8245b-111">Gets or sets a value that indicates whether the hostname is used to reach the service when matching on the URI.</span></span></summary>
        <value><span data-ttu-id="8245b-112">Ein gültiger HostnameComparisonMode-Wert, der angibt, ob der Hostname beim routing eingehender Anfragen an einen Endpunkt-URI eingeschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="8245b-112">A valid HostnameComparisonMode value that indicates whether the hostname is included when routing incoming requests to an endpoint URI.</span></span> <span data-ttu-id="8245b-113">Der Standardwert ist StrongWildcard, wodurch der Hostname beim Abgleich ignoriert wird.</span><span class="sxs-lookup"><span data-stu-id="8245b-113">The default value is StrongWildcard, which ignores the hostname in the match.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="8245b-114">Ruft die maximale Größe des zu verwendenden Puffers ab oder legt diese fest.</span><span class="sxs-lookup"><span data-stu-id="8245b-114">Gets or sets the maximum size of the buffer to use.</span></span></summary>
        <value><span data-ttu-id="8245b-115">Die maximale Anzahl an Bytes, die verwendet wird, um eingehende Nachrichten im Arbeitsspeicher zu puffern.</span><span class="sxs-lookup"><span data-stu-id="8245b-115">The maximum number of bytes that are used to buffer incoming messages in memory.</span></span> <span data-ttu-id="8245b-116">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="8245b-116">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.TimeSpanOrInfiniteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxOutputDelay", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8245b-117">Ruft das maximale Zeitintervall ab oder legt das maximale Zeitintervall fest, das als Teil einer Meldung oder vollständigen Meldung im Arbeitsspeicher gepuffert bleiben kann, bevor sie versendet wird.</span><span class="sxs-lookup"><span data-stu-id="8245b-117">Gets or sets the maximum interval of time that a part of a message or a full message can remain buffered in memory before being sent out.</span></span></summary>
        <value><span data-ttu-id="8245b-118">Das maximale Zeitintervall, das als Teil einer Nachricht oder als vollständige Nachricht bleiben kann im Arbeitsspeicher gepuffert werden, bevor Sie versendet wird. Der Standardwert beträgt 2 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="8245b-118">The maximum interval of time that a part of a message or a full message can remain buffered in memory before being sent out. The default value is 2 seconds.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxPendingAccepts", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8245b-119">Ruft die maximale Anzahl ausstehender asynchroner Annahmethreads ab, die für die Verarbeitung eingehender Verbindungen beim Dienst zur Verfügung stehen, oder legt die maximale Anzahl fest.</span><span class="sxs-lookup"><span data-stu-id="8245b-119">Gets or sets the maximum number of pending asynchronous accept threads that are available for processing incoming connections on the service.</span></span></summary>
        <value><span data-ttu-id="8245b-120">Die maximale Anzahl ausstehender Meldungen, die der Dienst annehmen kann.</span><span class="sxs-lookup"><span data-stu-id="8245b-120">The maximum number of pending messages the service can accept.</span></span> <span data-ttu-id="8245b-121">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="8245b-121">The default value is 1.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxPendingConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8245b-122">Ruft die maximale Anzahl ausstehender Verbindungen ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="8245b-122">Gets or sets the maximum number of pending connections.</span></span></summary>
        <value><span data-ttu-id="8245b-123">Die maximale Anzahl ausstehender Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="8245b-123">The maximum number of pending connections.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8245b-124">Ruft eine ConfigurationPropertyCollection-Instanz, die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält.</span><span class="sxs-lookup"><span data-stu-id="8245b-124">Gets a ConfigurationPropertyCollection instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></summary>
        <value><span data-ttu-id="8245b-125">Gibt eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> Instanz, die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält.</span><span class="sxs-lookup"><span data-stu-id="8245b-125">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.TransferMode" />
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
        <summary><span data-ttu-id="8245b-126">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Meldungen bei verbindungsorientiertem Transport gepuffert oder per Stream übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="8245b-126">Gets or sets a value that specifies whether the messages are buffered or streamed with the connection-oriented transport.</span></span></summary>
        <value><span data-ttu-id="8245b-127">Gibt eine gültige <see cref="T:System.ServiceModel.TransferMode" /> Wert, der angibt, ob ein Kanal verwendet den Stream- oder Puffermodus für die nachrichtenübertragung.</span><span class="sxs-lookup"><span data-stu-id="8245b-127">Returns a valid <see cref="T:System.ServiceModel.TransferMode" /> value that specifies whether a channel uses streamed or buffered modes of message transfer.</span></span> <span data-ttu-id="8245b-128">Der Standardwert ist Buffered.</span><span class="sxs-lookup"><span data-stu-id="8245b-128">The default is Buffered.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>