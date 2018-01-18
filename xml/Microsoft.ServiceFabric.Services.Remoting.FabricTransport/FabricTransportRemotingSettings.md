<Type Name="FabricTransportRemotingSettings" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings">
  <TypeSignature Language="C#" Value="public class FabricTransportRemotingSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportRemotingSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportRemotingSettings" />
  <TypeSignature Language="F#" Value="type FabricTransportRemotingSettings = class" />
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
            <span data-ttu-id="5dbaf-101">Stellt eine Einstellungen, die die FabricTransport-Kommunikation konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-101">Represents a settings that configures the  FabricTransport communication.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportRemotingSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5dbaf-102">Erstellt eine neue FabricTransportRemotingSettings mit Standardwerten.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-102">Creates a new FabricTransportRemotingSettings with default Values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />
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
            <span data-ttu-id="5dbaf-103">Ruft ab oder legt die maximale Zeitspanne für die Verbindung erfolgreich hergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-103">Gets or sets the maximum time allowed for the connection to be established successfully.</span></span>
            </summary>
        <value><span data-ttu-id="5dbaf-104">Die ConnectTimeout als <see cref="T:System.TimeSpan" />.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-104">The ConnectTimeout as <see cref="T:System.TimeSpan" />.</span></span></value>
        <remarks><span data-ttu-id="5dbaf-105">Standardwert für ConnectTimeout Timeout wird als 5 Sekunden festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-105">Default Value for ConnectTimeout Timeout is set as 5 seconds.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderBufferSize">
      <MemberSignature Language="C#" Value="public int HeaderBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderBufferSize : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderBufferSize" />
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
            <span data-ttu-id="5dbaf-106">HeaderBufferSize stellt die Größe jedes einzelnen Puffers Header in der BufferPool dar.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-106">HeaderBufferSize represents size of each header buffer in the bufferPool .</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
                <span data-ttu-id="5dbaf-107">Standard-Wert für die HeaderBufferSize ist 1024 Byte.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-107">Defaults  value for the HeaderBufferSize is 1024 bytes.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderMaxBufferCount">
      <MemberSignature Language="C#" Value="public int HeaderMaxBufferCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderMaxBufferCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderMaxBufferCount" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderMaxBufferCount As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderMaxBufferCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderMaxBufferCount" />
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
            <span data-ttu-id="5dbaf-108">HeaderMaxBufferCount stellt die maximale Anzahl der Header-Puffer der BufferPool zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-108">HeaderMaxBufferCount represents the maximum number of header buffers assigned  to the BufferPool.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
                <span data-ttu-id="5dbaf-109">Standard-Wert für die HeaderMaxBufferCount ist 1000.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-109">Defaults  value for the HeaderMaxBufferCount is 1000.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan KeepAliveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KeepAliveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />
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
            <span data-ttu-id="5dbaf-110">Abrufen oder Festlegen der KeepAliveTimeout, die eine Möglichkeit zum Konfigurieren der TCP-Keep-alive-Option bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-110">Gets or sets the KeepAliveTimeout that provides a way to configure  Tcp keep-alive option.</span></span>
            </summary>
        <value><span data-ttu-id="5dbaf-111">Die KeepAliveTimeout als <see cref="T:System.TimeSpan" />.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-111">The KeepAliveTimeout as <see cref="T:System.TimeSpan" />.</span></span></value>
        <remarks><span data-ttu-id="5dbaf-112">Standardwert für KeepAliveTimeout Timeout wird als TimeSpan.Zero festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-112">Default Value for KeepAliveTimeout Timeout is set as TimeSpan.Zero.</span></span> <span data-ttu-id="5dbaf-113">Gibt an, dass wir die Tcp Keepalive-Option deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-113">which indicates we disable the tcp keepalive option.</span></span>
            <span data-ttu-id="5dbaf-114">Wenn Sie Loadbalancer verwenden, müssen Sie diese konfigurieren, um die Loadbalancer zum Schließen der Verbindung einem bestimmten Zeitpunkt zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-114">If you are using loadbalancer , you may need to configure this in order to avoid  the loadbalancer to close the connection after certain time.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings LoadFrom (string sectionName, string filepath = null, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings LoadFrom(string sectionName, string filepath, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.LoadFrom(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function LoadFrom (sectionName As String, Optional filepath As String = null, Optional configPackageName As String = null) As FabricTransportRemotingSettings" />
      <MemberSignature Language="F#" Value="static member LoadFrom : string * string * string -&gt; Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.LoadFrom (sectionName, filepath, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="filepath" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName"><span data-ttu-id="5dbaf-115">Der Name des Abschnitts in der Konfigurationsdatei.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-115">The name of the section within the configuration file.</span></span> <span data-ttu-id="5dbaf-116">Wenn keine gefunden Abschnitt in der Konfigurationsdatei wird ArgumentException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-116">If not found section in configuration file, it will throw ArgumentException.</span></span></param>
        <param name="filepath"><span data-ttu-id="5dbaf-117">Der vollständige Pfad der Datei, in dem die Einstellungen aus geladen werden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-117">The full path of the file where the settings will be loaded from.</span></span> <span data-ttu-id="5dbaf-118">Wenn nicht angegeben, wird zuerst versucht, Standardwert Konfigurationspaket "Config" laden, wenn es gefunden anschließend Laden von Einstellungen für "ClientExeName.Settings.xml", die im Client Ausführungsverzeichnis vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-118">If not specified , it will first try to load from default Config Package"Config" , if not found then load from Settings "ClientExeName.Settings.xml" present in Client Exe directory.</span></span> </param>
        <param name="configPackageName"> <span data-ttu-id="5dbaf-119">Der Name des Konfigurationspakets. Wenn die Null oder leer, es für die Datei in den FilePath überprüft.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-119">Name of the configuration package.If its null or empty,it will check for file in filePath.</span></span></param>
        <summary>
            <span data-ttu-id="5dbaf-120">Lädt die FabricTransport-Einstellungen aus einem SectionName in der Konfigurationsdatei angegeben.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-120">Loads the FabricTransport settings from a sectionName specified in the configuration file.</span></span> <span data-ttu-id="5dbaf-121">Konfigurationsdatei kann angegeben werden, mithilfe den Dateipfad oder den Namen des Konfigurationspakets in das Manifest angegeben.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-121">Configuration File can be specified using the filePath or using the name of the configuration package specified in the service manifest.</span></span>
            <span data-ttu-id="5dbaf-122">Zunächst wird versucht, mit ConfigPackageName Config zu laden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-122">It will first try to load config using configPackageName.</span></span> <span data-ttu-id="5dbaf-123">Wenn ConfigPackageName nicht angegeben ist wiederholen Sie dann aus dem Dateipfad geladen.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-123">If configPackageName is not specified then try to load from filePath.</span></span>
            </summary>
        <returns><span data-ttu-id="5dbaf-124">Die FabricTransportRemotingSettings</span><span class="sxs-lookup"><span data-stu-id="5dbaf-124">The FabricTransportRemotingSettings</span></span></returns>
        <remarks>
            <span data-ttu-id="5dbaf-125">Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-125">The following are the parameter names that should be provided in the configuration file, to be recognizable by service fabric to load the transport settings.</span></span>
                
                1. <span data-ttu-id="5dbaf-126">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-126">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />value in long.</span></span>
                2. <span data-ttu-id="5dbaf-127">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-127">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />value in bytes.</span></span>
                3. <span data-ttu-id="5dbaf-128">Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-128">MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />value in long.</span></span>
                4. <span data-ttu-id="5dbaf-129">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-129">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> value.</span></span>
                5. <span data-ttu-id="5dbaf-130">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-130">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> value in seconds.</span></span>
                6. <span data-ttu-id="5dbaf-131">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-131">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> value in seconds.</span></span>
                7. <span data-ttu-id="5dbaf-132">ConnectTimeoutInMilliseconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" /> Wert in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-132">ConnectTimeoutInMilliseconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" /> value in milliseconds.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public long MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />
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
            <span data-ttu-id="5dbaf-133">Ruft ab oder legt die maximale Anzahl von Nachrichten aktiv Dienstprozesse auf einmal.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-133">Gets or sets the maximum number of messages actively service processes at one time.</span></span>
             </summary>
        <value>
            <span data-ttu-id="5dbaf-134">Der Drosselungen für MaxConcurrentCalls ist die Obergrenze aktiver Nachrichten im Dienst.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-134">The MaxConcurrentCalls is  the upper limit of active messages in the service.</span></span>
             </value>
        <remarks>
                <span data-ttu-id="5dbaf-135">Standardwert für den Drosselungen für MaxConcurrentCalls ist 16 \* Anzahl der Prozessoren.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-135">Default  value for the MaxConcurrentCalls is 16\*Number of processors.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />
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
            <span data-ttu-id="5dbaf-136">Ruft ab oder legt die maximale Größe für eine Nachricht, die empfangen werden kann, in einem Kanal, der mit dieser Einstellung konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-136">Gets or sets the maximum size for a message that can be received on a channel configured with this setting.</span></span>
            </summary>
        <value><span data-ttu-id="5dbaf-137">Die maximale Größe der Nachricht in Bytes.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-137">The maximum size of the message in bytes.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="5dbaf-138">Standardwert für MaxMessageSize verwendet beträgt 4.194.304 bytes</span><span class="sxs-lookup"><span data-stu-id="5dbaf-138">Default Value for MaxMessageSize used is 4194304 bytes</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxQueueSize">
      <MemberSignature Language="C#" Value="public long MaxQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxQueueSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxQueueSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />
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
            <span data-ttu-id="5dbaf-139">Ruft ab oder legt die maximale Größe einer Warteschlange, die Nachrichten speichert, während sie für einen mit dieser Einstellung konfigurierten Endpunkt verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-139">Gets or sets the maximum size, of a queue that stores messages while they are processed for an endpoint configured with this setting.</span></span> 
            </summary>
        <value><span data-ttu-id="5dbaf-140">Die maximale Größe für eine Warteschlange, die Nachrichten aus dem Kanal empfängt.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-140">The maximum size for a Queue that receives messages from the channel.</span></span> 
            </value>
        <remarks>
            <span data-ttu-id="5dbaf-141">Standardwert ist 10.000 Nachrichten</span><span class="sxs-lookup"><span data-stu-id="5dbaf-141">Default value is 10,000 messages</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />
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
            <span data-ttu-id="5dbaf-142">Abrufen oder Festlegen des Vorgangs Timeout zur Regelung den gesamten Prozess des Sendens einer Nachricht, einschließlich, empfängt eine Antwortnachricht für einen Anforderung/Antwort-Dienstvorgang.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-142">Gets or sets the operation Timeout  which governs the whole process of sending a message, including receiving a reply message for a request/reply service operation.</span></span>
             <span data-ttu-id="5dbaf-143">Dieses Timeout gilt auch beim Senden von Antwortnachrichten von einer Rückrufvertragsmethode.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-143">This timeout also applies when sending reply messages from a callback contract method.</span></span>
            </summary>
        <value><span data-ttu-id="5dbaf-144">Der OperationTimeout als <see cref="T:System.TimeSpan" />.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-144">The OperationTimeout as <see cref="T:System.TimeSpan" />.</span></span></value>
        <remarks><span data-ttu-id="5dbaf-145">Standardwert für das Timeout des Vorgangs wird als 5 Minuten festgelegt.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-145">Default Value for Operation Timeout is set as 5 mins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />
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
             <span data-ttu-id="5dbaf-146">Ruft ab oder legt die Anmeldeinformationen für das Sichern der Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-146">Gets or sets the security credentials for securing the communication.</span></span> 
             </summary>
        <value><span data-ttu-id="5dbaf-147">Die Anmeldeinformationen sollten als <see cref="T:System.Fabric.SecurityCredentials" />.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-147">The security credentials as  <see cref="T:System.Fabric.SecurityCredentials" />.</span></span>
             </value>
        <remarks>
             <span data-ttu-id="5dbaf-148">Standardwert für SecurityCredentials ist None.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-148">Default Value for SecurityCredentials is None.</span></span>
             <span data-ttu-id="5dbaf-149">SecurityCredential kann der Typ x509SecurityCredentail <seealso cref="T:System.Fabric.X509Credentials" />oder WindowsCredentials <seealso cref="T:System.Fabric.WindowsCredentials" />.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-149">SecurityCredential can be of type x509SecurityCredentail <seealso cref="T:System.Fabric.X509Credentials" />or WindowsCredentials <seealso cref="T:System.Fabric.WindowsCredentials" />.</span></span>
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryLoadFrom">
      <MemberSignature Language="C#" Value="public static bool TryLoadFrom (string sectionName, out Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings settings, string filepath = null, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryLoadFrom(string sectionName, [out] class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings&amp; settings, string filepath, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.TryLoadFrom(System.String,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings@,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryLoadFrom (sectionName As String, ByRef settings As FabricTransportRemotingSettings, Optional filepath As String = null, Optional configPackageName As String = null) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryLoadFrom : string *  * string * string -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.TryLoadFrom (sectionName, settings, filepath, configPackageName)" />
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
        <Parameter Name="settings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings&amp;" RefType="out" />
        <Parameter Name="filepath" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName"><span data-ttu-id="5dbaf-150">Der Name des Abschnitts in der Konfigurationsdatei.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-150">The name of the section within the configuration file.</span></span> <span data-ttu-id="5dbaf-151">Wenn keine gefunden Abschnitt in der Konfigurationsdatei es "false" zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-151">If not found section in configuration file, it return false.</span></span></param>
        <param name="settings"><span data-ttu-id="5dbaf-152">Wenn diese Methode zurückgegeben wird das <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" /> Einstellungen Wenn von der Konfiguration erfolgreich laden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-152">When this method returns it sets the <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" /> settings if load from Config succeeded.</span></span> <span data-ttu-id="5dbaf-153">Wenn ein Fehler auftritt, legt Einstellungen auf null.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-153">If fails, its sets settings to null.</span></span> </param>
        <param name="filepath"><span data-ttu-id="5dbaf-154">Der vollständige Pfad der Datei, in dem die Einstellungen aus geladen werden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-154">The full path of the file where the settings will be loaded from.</span></span> <span data-ttu-id="5dbaf-155">Wenn nicht angegeben, wird zuerst versucht, Standardwert Konfigurationspaket "Config" laden, wenn es gefunden anschließend Laden von Einstellungen für "ClientExeName.Settings.xml", die im Client Ausführungsverzeichnis vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-155">If not specified , it will first try to load from default Config Package"Config" , if not found then load from Settings "ClientExeName.Settings.xml" present in Client Exe directory.</span></span> </param>
        <param name="configPackageName"><span data-ttu-id="5dbaf-156">Der Name des Konfigurationspakets.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-156">The name of the configuration package.</span></span> <span data-ttu-id="5dbaf-157">Wenn die Null oder leer, es für die Datei in den FilePath überprüft.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-157">If its null or empty, it will check for file in filePath.</span></span></param>
        <summary>
            <span data-ttu-id="5dbaf-158">Versuchen Sie, die FabricTransport-Einstellungen aus einer in der Konfigurationsdatei angegebenen SectionName zu laden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-158">Try to load the FabricTransport settings from a sectionName specified in the configuration file.</span></span>
            <span data-ttu-id="5dbaf-159">Konfigurationsdatei kann angegeben werden, mithilfe den Dateipfad oder den Namen des Konfigurationspakets in das Manifest angegeben.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-159">Configuration File can be specified using the filePath or using the name of the configuration package specified in the service manifest.</span></span>
            <span data-ttu-id="5dbaf-160">Zunächst wird versucht, mit ConfigPackageName Config zu laden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-160">It will first try to load config using configPackageName.</span></span> <span data-ttu-id="5dbaf-161">Wenn ConfigPackageName nicht angegeben ist wiederholen Sie dann aus dem Dateipfad geladen.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-161">If configPackageName is not specified then try to load from filePath.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5dbaf-162"><see cref="T:System.Boolean" />Gibt an, ob die Einstellungen aus der Konfiguration erfolgreich geladen. Gibt true zurück, wenn von der Konfiguration erfolgreich laden, andernfalls "false" zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-162"><see cref="T:System.Boolean" /> specifies whether the settings get loaded successfully from Config. It returns true when load from Config succeeded, else return false.</span></span> </returns>
        <remarks>
            <span data-ttu-id="5dbaf-163">Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-163">The following are the parameter names that should be provided in the configuration file,to be recognizable by service fabric to load the transport settings.</span></span>
                
                1. <span data-ttu-id="5dbaf-164">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-164">MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />value in long.</span></span>
                2. <span data-ttu-id="5dbaf-165">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-165">MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />value in bytes.</span></span>
                3. <span data-ttu-id="5dbaf-166">Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-166">MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />value in long.</span></span>
                4. <span data-ttu-id="5dbaf-167">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-167">SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> value.</span></span>
                5. <span data-ttu-id="5dbaf-168">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-168">OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> value in seconds.</span></span>
                6. <span data-ttu-id="5dbaf-169">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-169">KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> value in seconds.</span></span>
                7. <span data-ttu-id="5dbaf-170">ConnectTimeoutInMilliseconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" /> Wert in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="5dbaf-170">ConnectTimeoutInMilliseconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" /> value in milliseconds.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>