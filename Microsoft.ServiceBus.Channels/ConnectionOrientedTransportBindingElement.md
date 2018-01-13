<Type Name="ConnectionOrientedTransportBindingElement" FullName="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement">
  <TypeSignature Language="C#" Value="public abstract class ConnectionOrientedTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConnectionOrientedTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConnectionOrientedTransportBindingElement&#xA;Inherits TransportBindingElement" />
  <TypeSignature Language="F#" Value="type ConnectionOrientedTransportBindingElement = class&#xA;    inherit TransportBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e25d9-101">Eine abstrakte Klasse, die das Basis-<see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> um zusätzliche Eigenschaften erweitert, die häufig bei verbindungsorientierten Transporten, z.&amp;#160;B. TCP und Named Pipes, verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e25d9-101">An abstract class that supplements the base <see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> with additional properties that are common to connection-oriented transports such as TCP and named pipes.</span></span>  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CanBuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of TChannel) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="connectionOrientedTransportBindingElement.CanBuildChannelFactory context" />
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
        <typeparam name="TChannel"></typeparam>
        <param name="context"><span data-ttu-id="e25d9-102">BindingContext für den Kanal.</span><span class="sxs-lookup"><span data-stu-id="e25d9-102">The BindingContext for the channel.</span></span></param>
        <summary>
            <span data-ttu-id="e25d9-103">Bestimmt, ob eine Kanalfactory des angegebenen Typs erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="e25d9-103">Determines whether a channel factory of the specified type can be built.</span></span>
            </summary>
        <returns><span data-ttu-id="e25d9-104">True, wenn IChannelListener&lt;TChannel&gt; des Typs IChannel kann durch das Bindungselement erstellt wurde, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e25d9-104">true if the IChannelListener&lt;TChannel&gt; of type IChannel can be built by the binding element; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="connectionOrientedTransportBindingElement.CanBuildChannelListener context" />
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
        <typeparam name="TChannel"></typeparam>
        <param name="context"><span data-ttu-id="e25d9-105">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="e25d9-105">The binding context that provides context for the binding element.</span></span></param>
        <summary>
            <span data-ttu-id="e25d9-106">Gibt einen Wert zurück, der angibt, ob das Bindungselement einen Listener für einen bestimmten Typ von Kanal erstellen kann.</span><span class="sxs-lookup"><span data-stu-id="e25d9-106">Returns a value that indicates whether the binding element can build a listener for a specific type of channel.</span></span>
            </summary>
        <returns><span data-ttu-id="e25d9-107">True, wenn IChannelListener&lt;TChannel&gt; des Typs IChannel kann durch das Bindungselement erstellt wurde, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e25d9-107">true if the IChannelListener&lt;TChannel&gt; of type IChannel can be built by the binding element; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-108">Ruft ab oder legt die Zeitspanne fest, die angibt, wie lange der kanalinitialisierung muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="e25d9-108">Gets or sets the timespan that specifies how long the channel initialization has to complete before timing out.</span></span></summary>
        <value><span data-ttu-id="e25d9-109">Gibt eine <see cref="T:System.TimeSpan" /> nach dem Timeout der Initialisierung.</span><span class="sxs-lookup"><span data-stu-id="e25d9-109">Returns a <see cref="T:System.TimeSpan" /> after which the initialization times out.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-110">Ermittelt und definiert die Größe des Puffers zum Übertragen eines Teils der serialisierten Nachricht über das Netzwerk vom Client oder Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="e25d9-110">Gets and sets the size of the buffer used to transmit a chunk of the serialized message on the wire from the client or service.</span></span> </summary>
        <value><span data-ttu-id="e25d9-111">Die Größe des Verbindungspuffers.</span><span class="sxs-lookup"><span data-stu-id="e25d9-111">The size of the connection buffer.</span></span> <span data-ttu-id="e25d9-112">Der Standardwert ist 8192 Bytes.</span><span class="sxs-lookup"><span data-stu-id="e25d9-112">The default value is 8192 bytes.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e25d9-113">Der Wert ist kleiner als 0 (null).</span><span class="sxs-lookup"><span data-stu-id="e25d9-113">The value is less than zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="connectionOrientedTransportBindingElement.GetProperty context" />
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
        <param name="context"><span data-ttu-id="e25d9-114">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="e25d9-114">The binding context that provides context for the binding element.</span></span></param>
        <summary>
            <span data-ttu-id="e25d9-115">Ruft Eigenschaften vom bindungsstapel, ab, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="e25d9-115">Retrieves properties from the binding stack, if present.</span></span>
            </summary>
        <returns><span data-ttu-id="e25d9-116">Ein Objekt des bindungsstapels, falls vorhanden, oder null, wenn nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="e25d9-116">An object from the binding stack, if present, or null if not found.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-117">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Hostname zum Erreichen des Diensts bei übereinstimmendem URI verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="e25d9-117">Gets or sets a value that indicates whether the hostname is used to reach the service when matching on the URI.</span></span></summary>
        <value><span data-ttu-id="e25d9-118">Gibt eine <see cref="T:System.ServiceModel.HostNameComparisonMode" /> , der bestimmt, ob der Hostname zum Erreichen des Diensts verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="e25d9-118">Returns a <see cref="T:System.ServiceModel.HostNameComparisonMode" /> that determines whether the hostname is used to reach the service.</span></span> <span data-ttu-id="e25d9-119">Der Standardwert ist StrongWildCard, wodurch der Hostname und Port-Nummer im Vergleich ignoriert.</span><span class="sxs-lookup"><span data-stu-id="e25d9-119">The default value is StrongWildCard, which ignores the hostname and port number in the comparison.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e25d9-120">Der Wert ist eine gültige HostnameComparisonMode.</span><span class="sxs-lookup"><span data-stu-id="e25d9-120">The value is not a valid HostnameComparisonMode.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-121">Ruft die maximale Größe des zu verwendenden Puffers ab oder legt diese fest.</span><span class="sxs-lookup"><span data-stu-id="e25d9-121">Gets or sets the maximum size of the buffer to use.</span></span></summary>
        <value><span data-ttu-id="e25d9-122">Die maximale Anzahl an Bytes, die verwendet wird, um eingehende Nachrichten im Arbeitsspeicher zu puffern.</span><span class="sxs-lookup"><span data-stu-id="e25d9-122">The maximum number of bytes that are used to buffer incoming messages in memory.</span></span> <span data-ttu-id="e25d9-123">Der Standardwert ist 65.536 Bytes.</span><span class="sxs-lookup"><span data-stu-id="e25d9-123">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e25d9-124">Der Wert ist kleiner als oder gleich 0&amp;#160;(null).</span><span class="sxs-lookup"><span data-stu-id="e25d9-124">The value is less than or equal to zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-125">Ruft das maximale Zeitintervall ab, oder legt das maximale Zeitintervall fest, das als Teil einer Nachricht oder als vollständige Nachricht im Arbeitsspeicher gepuffert bleiben kann, bevor sie versendet wird.</span><span class="sxs-lookup"><span data-stu-id="e25d9-125">Gets or sets the maximum interval of time that a chunk of a message or a full message can remain buffered in memory before being sent out.</span></span></summary>
        <value><span data-ttu-id="e25d9-126">Gibt eine <see cref="T:System.TimeSpan" /> , der angibt, dass des maximale Zeitintervall, das als Teil einer Nachricht oder vollständigen Meldung im Arbeitsspeicher gepuffert bleiben kann, bevor Sie versendet wird. Der Standardwert beträgt 2 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="e25d9-126">Returns a <see cref="T:System.TimeSpan" /> that specifies the maximum interval of time that a chunk of a message or a full message can remain buffered in memory before being sent out. The default value is 2 seconds.</span></span> <span data-ttu-id="e25d9-127">Diese Eigenschaft ist nur sinnvoll, wenn die Eigenschaft AllowedOutputBatching einer ausgehenden Nachricht festgelegt ist auf "true".</span><span class="sxs-lookup"><span data-stu-id="e25d9-127">This property is only meaningful if the AllowedOutputBatching property of an outgoing message is set to true.</span></span> <span data-ttu-id="e25d9-128">Andernfalls wird dieser Wert ignoriert, und die Nachrichten werden sofort gesendet.</span><span class="sxs-lookup"><span data-stu-id="e25d9-128">Otherwise, this value is ignored and messages are sent immediately.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e25d9-129">Der Wert ist kleiner als 0 (null).</span><span class="sxs-lookup"><span data-stu-id="e25d9-129">The value is less than zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-130">Ruft die maximale Anzahl ausstehender asynchroner Annahmevorgänge ab, die für die Verarbeitung beim Dienst eingehender Verbindungen zur Verfügung stehen, oder legt die maximale Anzahl fest.</span><span class="sxs-lookup"><span data-stu-id="e25d9-130">Gets or sets the maximum number of pending asynchronous accept operations that are available for processing incoming connections to the service.</span></span></summary>
        <value><span data-ttu-id="e25d9-131">Die maximale Anzahl an Verbindungen, die der Dienst gleichzeitig annehmen kann.</span><span class="sxs-lookup"><span data-stu-id="e25d9-131">The maximum number of connections the service can accept simultaneously.</span></span> <span data-ttu-id="e25d9-132">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="e25d9-132">The default value is 1.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e25d9-133">Der Wert ist kleiner als oder gleich 0&amp;#160;(null).</span><span class="sxs-lookup"><span data-stu-id="e25d9-133">The value is less than or equal to zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-134">Ruft die maximale Anzahl an Verbindungen ab, die zum Verteilen auf dem Dienst bereitstehen, oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="e25d9-134">Gets or sets the maximum number of connections awaiting dispatch on the service.</span></span></summary>
        <value><span data-ttu-id="e25d9-135">Die maximale Anzahl eingehender und am Dienst zur Verteilung bereitstehender Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="e25d9-135">The maximum number of inbound connections awaiting dispatch on the service.</span></span> <span data-ttu-id="e25d9-136">Der Standardwert ist 10.</span><span class="sxs-lookup"><span data-stu-id="e25d9-136">The default value is 10.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e25d9-137">Der Wert ist kleiner als oder gleich 0&amp;#160;(null).</span><span class="sxs-lookup"><span data-stu-id="e25d9-137">The value is less than or equal to zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e25d9-138">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Meldungen bei verbindungsorientiertem Transport gepuffert oder per Stream übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="e25d9-138">Gets or sets a value that specifies whether the messages are buffered or streamed with the connection-oriented transport.</span></span></summary>
        <value><span data-ttu-id="e25d9-139">Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> Streaming- oder Puffermodus für die nachrichtenübertragung gibt an, ob ein Kanal verwendet.</span><span class="sxs-lookup"><span data-stu-id="e25d9-139">Returns a <see cref="T:System.ServiceModel.TransferMode" /> which indicates whether a channel uses streamed or buffered modes of message transfer.</span></span> <span data-ttu-id="e25d9-140">Der Standardwert ist Buffered.</span><span class="sxs-lookup"><span data-stu-id="e25d9-140">The default is Buffered.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="e25d9-141">Der Wert ist eine gültige Übertragungsmodus.</span><span class="sxs-lookup"><span data-stu-id="e25d9-141">The value is not a valid TransferMode.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>