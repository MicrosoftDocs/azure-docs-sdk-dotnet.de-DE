<Type Name="FabricTransportRemotingListenerSettings" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings">
  <TypeSignature Language="C#" Value="public class FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportRemotingListenerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="F#" Value="type FabricTransportRemotingListenerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7e06b-101">Einstellungen, die den FabricTransport-Listener konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-101">Settings that configures the  FabricTransport Listener.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportRemotingListenerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-102">Erstellt eine neue Instanz der FabricTransportRemotingListenerSettings und Eigenschaften mit den Standardwerten initialisiert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-102">Creates a new instance of FabricTransportRemotingListenerSettings and initializes properties with default Values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointResourceName">
      <MemberSignature Language="C#" Value="public string EndpointResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.EndpointResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointResourceName As String" />
      <MemberSignature Language="F#" Value="member this.EndpointResourceName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.EndpointResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-103">EndpointResourceName handelt es sich um die Namen der endpunktressource in ServiceManifest angegeben. Dient zum Abrufen der Portnummer auf dem Dienst überwacht.</span><span class="sxs-lookup"><span data-stu-id="7e06b-103">EndpointResourceName is name of the endpoint resource specified in ServiceManifest .This is used to obtain the port number on which to service will listen.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="7e06b-104">EndpointResourceName ist der Name der endpunktressource im Dienstmanifest definiert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-104">EndpointResourceName is  name of the  endpoint resource defined in the service manifest.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="7e06b-105">Standardwert EndpointResourceName ist "ServiceEndpoint"</span><span class="sxs-lookup"><span data-stu-id="7e06b-105">Default value of EndpointResourceName  is "ServiceEndpoint"</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderBufferSize">
      <MemberSignature Language="C#" Value="public int HeaderBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderBufferSize : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-106">HeaderBufferSize stellt die Größe jedes einzelnen Puffers Header in der BufferPool dar.</span><span class="sxs-lookup"><span data-stu-id="7e06b-106">HeaderBufferSize represents size of each header buffer in the bufferPool .</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
                <span data-ttu-id="7e06b-107">Standard-Wert für die HeaderBufferSize ist 1024 Byte.</span><span class="sxs-lookup"><span data-stu-id="7e06b-107">Defaults  value for the HeaderBufferSize is 1024 bytes.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderMaxBufferCount">
      <MemberSignature Language="C#" Value="public int HeaderMaxBufferCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderMaxBufferCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderMaxBufferCount" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderMaxBufferCount As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderMaxBufferCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderMaxBufferCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-108">HeaderMaxBufferCount stellt die maximale Anzahl der Header-Puffer der BufferPool zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="7e06b-108">HeaderMaxBufferCount represents the maximum number of header buffers assigned  to the BufferPool.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
                <span data-ttu-id="7e06b-109">Standard-Wert für die HeaderMaxBufferCount ist 1000.</span><span class="sxs-lookup"><span data-stu-id="7e06b-109">Defaults  value for the HeaderMaxBufferCount is 1000.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan KeepAliveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KeepAliveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.KeepAliveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.KeepAliveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-110">KeepAliveTimeout ist, bietet eine Möglichkeit zum Konfigurieren der TCP-Keep-alive-Option.</span><span class="sxs-lookup"><span data-stu-id="7e06b-110">KeepAliveTimeout is provides a way to configure  Tcp keep-alive option.</span></span>
            </summary>
        <value><span data-ttu-id="7e06b-111">KeepAliveTimeout als<see cref="T:System.TimeSpan" /></span><span class="sxs-lookup"><span data-stu-id="7e06b-111">KeepAliveTimeout as <see cref="T:System.TimeSpan" /></span></span></value>
        <remarks><span data-ttu-id="7e06b-112">Standardwert für KeepAliveTimeout Timeout wird als TimeSpan.Zero festgelegt.</span><span class="sxs-lookup"><span data-stu-id="7e06b-112">Default Value for KeepAliveTimeout Timeout is set as TimeSpan.Zero.</span></span> <span data-ttu-id="7e06b-113">Gibt an, dass wir die Tcp Keepalive-Option deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="7e06b-113">which indicates we disable the tcp keepalive option.</span></span>
            <span data-ttu-id="7e06b-114">Wenn Sie Loadbalancer verwenden, müssen Sie möglicherweise konfigurieren, um die Loadbalancer zum Schließen der Verbindung einem bestimmten Zeitpunkt zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="7e06b-114">If you are using loadbalancer , you may need to configure this in order to avoid  the loadbalancer to close the connection after certain time</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings LoadFrom (string sectionName, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings LoadFrom(string sectionName, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.LoadFrom(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function LoadFrom (sectionName As String, Optional configPackageName As String = null) As FabricTransportRemotingListenerSettings" />
      <MemberSignature Language="F#" Value="static member LoadFrom : string * string -&gt; Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.LoadFrom (sectionName, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName"><span data-ttu-id="7e06b-115">Der Name des Abschnitts in der Konfigurationsdatei.</span><span class="sxs-lookup"><span data-stu-id="7e06b-115">Name of the section within the configuration file.</span></span> <span data-ttu-id="7e06b-116">Wenn es nicht gefunden, löst ArgumentException.</span><span class="sxs-lookup"><span data-stu-id="7e06b-116">if not found , it throws ArgumentException.</span></span></param>
        <param name="configPackageName"> <span data-ttu-id="7e06b-117">Der Name des Konfigurationspakets.</span><span class="sxs-lookup"><span data-stu-id="7e06b-117">Name of the configuration package.</span></span> <span data-ttu-id="7e06b-118">Wenn nicht gefunden "Settings.xml" in der Pfad des Pakets wird ArgumentException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="7e06b-118">if not found Settings.xml in the configuration package path, it throws ArgumentException.</span></span> <span data-ttu-id="7e06b-119">Wenn nicht angegeben ist, lautet der Standardname "Config"</span><span class="sxs-lookup"><span data-stu-id="7e06b-119">If not specified, default name is "Config"</span></span></param>
        <summary>
            <span data-ttu-id="7e06b-120">Lädt die FabricTransport-Einstellungen von einem Abschnitt in der Konfigurationsdatei der Settings - angegeben "Settings.xml"</span><span class="sxs-lookup"><span data-stu-id="7e06b-120">Loads the FabricTransport settings from a section specified in the service settings configuration file - settings.xml</span></span> 
            </summary>
        <returns><span data-ttu-id="7e06b-121">FabricTransportRemotingListenerSettings</span><span class="sxs-lookup"><span data-stu-id="7e06b-121">FabricTransportRemotingListenerSettings</span></span></returns>
        <remarks>
            <span data-ttu-id="7e06b-122">Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7e06b-122">The following are the parameter names that should be provided in the configuration file,to be recognizable by service fabric to load the transport settings.</span></span>
                
                1. <span data-ttu-id="7e06b-123">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-123">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />value in long.</span></span>
                2. <span data-ttu-id="7e06b-124">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.</span><span class="sxs-lookup"><span data-stu-id="7e06b-124">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />value in bytes.</span></span>
                3. <span data-ttu-id="7e06b-125">Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-125">MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />value in long.</span></span>
                4. <span data-ttu-id="7e06b-126">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-126">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> value.</span></span>
                5. <span data-ttu-id="7e06b-127">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="7e06b-127">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> value in seconds.</span></span>
                6. <span data-ttu-id="7e06b-128">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="7e06b-128">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> value in seconds.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public long MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxConcurrentCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-129">Drosselungen für MaxConcurrentCalls stellt maximale Anzahl von Nachrichten Dienst aktiv Prozesse gleichzeitig.</span><span class="sxs-lookup"><span data-stu-id="7e06b-129">MaxConcurrentCalls represents maximum number of messages actively service processes at one time.</span></span>
             </summary>
        <value>
            <span data-ttu-id="7e06b-130">Drosselungen für MaxConcurrentCalls ist die Obergrenze aktiver Nachrichten im Dienst.</span><span class="sxs-lookup"><span data-stu-id="7e06b-130">MaxConcurrentCalls is  the upper limit of active messages in the service.</span></span>
             </value>
        <remarks>
                <span data-ttu-id="7e06b-131">Standardwerte-Wert für den Drosselungen für MaxConcurrentCalls liegt und die Anzahl der Prozessoren.</span><span class="sxs-lookup"><span data-stu-id="7e06b-131">Defaults  value for the MaxConcurrentCalls is to the Number of processors.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-132">MaxMessageSize stellt die maximale Größe für eine Nachricht, die in einem mit dieser Einstellung konfigurierten Kanal beim Nachrichtenempfang zulässig.</span><span class="sxs-lookup"><span data-stu-id="7e06b-132">MaxMessageSize represents  the maximum size for a message that can be received on a channel configured with this setting.</span></span>
            </summary>
        <value><span data-ttu-id="7e06b-133">Maximale Größe der Nachricht in Bytes.</span><span class="sxs-lookup"><span data-stu-id="7e06b-133">Maximum size of the message in bytes.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="7e06b-134">Standardwert für MaxMessageSize verwendet beträgt 4.194.304 bytes</span><span class="sxs-lookup"><span data-stu-id="7e06b-134">Default Value for MaxMessageSize used is 4194304 bytes</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxQueueSize">
      <MemberSignature Language="C#" Value="public long MaxQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxQueueSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxQueueSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-135">Die maximale Größe einer Warteschlange, die Nachrichten speichert, während sie für einen mit dieser Einstellung konfigurierten Endpunkt verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="7e06b-135">The maximum size, of a queue that stores messages while they are processed for an endpoint configured with this setting.</span></span> 
            </summary>
        <value> <span data-ttu-id="7e06b-136">Max Size für eine Warteschlange, die Nachrichten aus dem Kanal empfängt.</span><span class="sxs-lookup"><span data-stu-id="7e06b-136">Max Size for a Queue that receives messages from the channel</span></span> 
            </value>
        <remarks>
            <span data-ttu-id="7e06b-137">Standardwert ist 10.000 Nachrichten</span><span class="sxs-lookup"><span data-stu-id="7e06b-137">Default value is 10,000 messages</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e06b-138">Timeout des Vorgangs zur Regelung den gesamten Prozess des Sendens einer Nachricht, einschließlich, empfängt eine Antwortnachricht für einen Anforderung/Antwort-Dienstvorgang.</span><span class="sxs-lookup"><span data-stu-id="7e06b-138">Operation Timeout  which governs the whole process of sending a message, including receiving a reply message for a request/reply service operation.</span></span>
             <span data-ttu-id="7e06b-139">Dieses Timeout gilt auch beim Senden von Antwortnachrichten von einer Rückrufvertragsmethode.</span><span class="sxs-lookup"><span data-stu-id="7e06b-139">This timeout also applies when sending reply messages from a callback contract method.</span></span>
            </summary>
        <value><span data-ttu-id="7e06b-140">OperationTimeout als<see cref="T:System.TimeSpan" /></span><span class="sxs-lookup"><span data-stu-id="7e06b-140">OperationTimeout as <see cref="T:System.TimeSpan" /></span></span></value>
        <remarks><span data-ttu-id="7e06b-141">Standardwert für das Timeout des Vorgangs ist als 5 Minuten festgelegt.</span><span class="sxs-lookup"><span data-stu-id="7e06b-141">Default Value for Operation Timeout is set as 5 mins</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="7e06b-142">Anmeldeinformationen für das Sichern der Kommunikation</span><span class="sxs-lookup"><span data-stu-id="7e06b-142">Security credentials for securing the communication</span></span> 
             </summary>
        <value><span data-ttu-id="7e06b-143">SecurityCredentials als<see cref="T:System.Fabric.SecurityCredentials" /></span><span class="sxs-lookup"><span data-stu-id="7e06b-143">SecurityCredentials as  <see cref="T:System.Fabric.SecurityCredentials" /></span></span></value>
        <remarks>
             <span data-ttu-id="7e06b-144">Standardwert für SecurityCredentials ist keine SecurityCredential möglich Typ x509SecurityCredentail <seealso cref="T:System.Fabric.X509Credentials" />oder WindowsCredentials<seealso cref="T:System.Fabric.WindowsCredentials" /></span><span class="sxs-lookup"><span data-stu-id="7e06b-144">Default Value for SecurityCredentials is None SecurityCredential can be of type x509SecurityCredentail <seealso cref="T:System.Fabric.X509Credentials" />or WindowsCredentials <seealso cref="T:System.Fabric.WindowsCredentials" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TryLoadFrom">
      <MemberSignature Language="C#" Value="public static bool TryLoadFrom (string sectionName, out Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings remotingListenerSettings, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryLoadFrom(string sectionName, [out] class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings&amp; remotingListenerSettings, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.TryLoadFrom(System.String,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings@,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryLoadFrom (sectionName As String, ByRef remotingListenerSettings As FabricTransportRemotingListenerSettings, Optional configPackageName As String = null) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryLoadFrom : string *  * string -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.TryLoadFrom (sectionName, remotingListenerSettings, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="remotingListenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings&amp;" RefType="out" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName"><span data-ttu-id="7e06b-145">Der Name des Abschnitts in der Konfigurationsdatei.</span><span class="sxs-lookup"><span data-stu-id="7e06b-145">Name of the section within the configuration file.</span></span> <span data-ttu-id="7e06b-146">Wenn Sie nicht gefunden, es "false" zurückgibt</span><span class="sxs-lookup"><span data-stu-id="7e06b-146">if not found , it return false</span></span></param>
        <param name="remotingListenerSettings"><span data-ttu-id="7e06b-147">Wenn diese Methode zurückgegeben wird das <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> Listenersettings Wenn von der Konfiguration erfolgreich laden.</span><span class="sxs-lookup"><span data-stu-id="7e06b-147">When this method returns it sets the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> listenersettings if load from Config succeeded.</span></span> <span data-ttu-id="7e06b-148">Wenn ein Fehler auftritt, wird seine legt ListenerSettings auf null /&gt;</span><span class="sxs-lookup"><span data-stu-id="7e06b-148">If fails ,its sets listenerSettings to null/&gt;</span></span> </param>
        <param name="configPackageName"> <span data-ttu-id="7e06b-149">Der Name des Konfigurationspakets.</span><span class="sxs-lookup"><span data-stu-id="7e06b-149">Name of the configuration package.</span></span> <span data-ttu-id="7e06b-150">Wenn nicht gefunden "Settings.xml" in der Pfad des Pakets, es gibt "false".</span><span class="sxs-lookup"><span data-stu-id="7e06b-150">if not found Settings.xml in the configuration package path, it return false.</span></span> <span data-ttu-id="7e06b-151">Wenn nicht angegeben ist, lautet der Standardname "Config"</span><span class="sxs-lookup"><span data-stu-id="7e06b-151">If not specified, default name is "Config"</span></span></param>
        <summary>
            <span data-ttu-id="7e06b-152">Die FabricTransport-Einstellungen von einem Abschnitt angegeben, in der Konfigurationsdatei der Settings - laden "Settings.xml"</span><span class="sxs-lookup"><span data-stu-id="7e06b-152">Try to load the FabricTransport settings from a section specified in the service settings configuration file - settings.xml</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="7e06b-153"><see cref="T:System.Boolean" />Gibt an, ob die Einstellungen aus der Konfiguration erfolgreich geladen. Gibt true zurück, wenn von der Konfiguration erfolgreich laden, andernfalls "false" zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="7e06b-153"><see cref="T:System.Boolean" /> specifies whether the settings get loaded successfully from Config. It returns true when load from Config succeeded, else return false.</span></span></returns>
        <remarks>
            <span data-ttu-id="7e06b-154">Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7e06b-154">The following are the parameter names that should be provided in the configuration file,to be recognizable by service fabric to load the transport settings.</span></span>
                
                1. <span data-ttu-id="7e06b-155">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-155">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />value in long.</span></span>
                2. <span data-ttu-id="7e06b-156">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.</span><span class="sxs-lookup"><span data-stu-id="7e06b-156">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />value in bytes.</span></span>
                3. <span data-ttu-id="7e06b-157">Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-157">MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />value in long.</span></span>
                4. <span data-ttu-id="7e06b-158">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="7e06b-158">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> value.</span></span>
                5. <span data-ttu-id="7e06b-159">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="7e06b-159">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> value in seconds.</span></span>
                6. <span data-ttu-id="7e06b-160">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="7e06b-160">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> value in seconds.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>