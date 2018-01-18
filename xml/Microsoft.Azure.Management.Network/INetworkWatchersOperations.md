<Type Name="INetworkWatchersOperations" FullName="Microsoft.Azure.Management.Network.INetworkWatchersOperations">
  <TypeSignature Language="C#" Value="public interface INetworkWatchersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkWatchersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.INetworkWatchersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkWatchersOperations" />
  <TypeSignature Language="F#" Value="type INetworkWatchersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="54107-101">NetworkWatchersOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="54107-101">NetworkWatchersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; BeginCheckConnectivityWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; BeginCheckConnectivityWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginCheckConnectivityWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCheckConnectivityWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;" Usage="iNetworkWatchersOperations.BeginCheckConnectivityWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-102">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-102">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-103">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-103">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-104">Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="54107-104">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-105">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-107">Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.</span><span class="sxs-lookup"><span data-stu-id="54107-107">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-108">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-109">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-110">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iNetworkWatchersOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, networkWatcherName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-111">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-111">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-112">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-112">The name of the network watcher.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-113">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-115">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="54107-115">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-116">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-117">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; BeginGetAzureReachabilityReportWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; BeginGetAzureReachabilityReportWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetAzureReachabilityReportWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetAzureReachabilityReportWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetAzureReachabilityReportWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-118">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-118">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-119">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-119">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-120">Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="54107-120">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-121">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-123">Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.</span><span class="sxs-lookup"><span data-stu-id="54107-123">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-124">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-125">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-125">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-126">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginGetFlowLogStatusWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginGetFlowLogStatusWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetFlowLogStatusWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetFlowLogStatusWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetFlowLogStatusWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-127">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-127">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-128">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-128">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-129">Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-129">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-130">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-132">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="54107-132">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-133">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-134">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-135">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; BeginGetNextHopWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; BeginGetNextHopWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetNextHopWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetNextHopWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetNextHopWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-136">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-137">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-137">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-138">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-138">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-139">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-141">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="54107-141">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-142">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-143">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-143">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-144">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingResultWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingResultWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetTroubleshootingResultWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetTroubleshootingResultWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetTroubleshootingResultWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-145">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-146">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-146">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-147">Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-147">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-148">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-150">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="54107-150">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-151">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-152">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-153">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; BeginGetTroubleshootingWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetTroubleshootingWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetTroubleshootingWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetTroubleshootingWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-154">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-155">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-155">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-156">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-156">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-157">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-157">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-159">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="54107-159">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-160">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-160">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-161">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-161">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-162">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-162">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; BeginGetVMSecurityRulesWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; BeginGetVMSecurityRulesWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginGetVMSecurityRulesWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetVMSecurityRulesWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginGetVMSecurityRulesWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-163">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-163">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-164">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-164">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-165">Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-165">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-166">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-168">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="54107-168">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-169">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-170">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-171">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProvidersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; BeginListAvailableProvidersWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; BeginListAvailableProvidersWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginListAvailableProvidersWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginListAvailableProvidersWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;" Usage="iNetworkWatchersOperations.BeginListAvailableProvidersWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-172">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-172">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-173">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-173">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-174">Parameter, die die Liste der verfügbaren Anbieter Bereich.</span><span class="sxs-lookup"><span data-stu-id="54107-174">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-175">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-175">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-177">Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.</span><span class="sxs-lookup"><span data-stu-id="54107-177">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-178">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-179">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-180">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-180">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginSetFlowLogConfigurationWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; BeginSetFlowLogConfigurationWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginSetFlowLogConfigurationWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetFlowLogConfigurationWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.BeginSetFlowLogConfigurationWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-181">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-181">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-182">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-182">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-183">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-183">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-184">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-186">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="54107-186">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-187">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-188">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-189">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; BeginVerifyIPFlowWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; BeginVerifyIPFlowWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.BeginVerifyIPFlowWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginVerifyIPFlowWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;" Usage="iNetworkWatchersOperations.BeginVerifyIPFlowWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-190">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-190">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-191">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-191">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-192">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-192">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-193">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-195">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="54107-195">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-196">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-197">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-198">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; CheckConnectivityWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt; CheckConnectivityWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.CheckConnectivityWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckConnectivityWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;" Usage="iNetworkWatchersOperations.CheckConnectivityWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-199">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-199">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-200">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-200">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-201">Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="54107-201">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-202">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-204">Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.</span><span class="sxs-lookup"><span data-stu-id="54107-204">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-205">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-206">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-207">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="iNetworkWatchersOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-208">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-208">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-209">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-209">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-210">Parameter, die die Watcher-Netzwerkressource definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-210">Parameters that define the network watcher resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-211">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-213">Erstellt oder aktualisiert eine netzwerküberwachung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-213">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-214">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-214">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-215">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-215">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-216">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-216">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iNetworkWatchersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, networkWatcherName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-217">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-217">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-218">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-218">The name of the network watcher.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-219">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-219">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-220">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-221">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="54107-221">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-222">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-222">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-223">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-223">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; GetAzureReachabilityReportWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt; GetAzureReachabilityReportWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetAzureReachabilityReportWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAzureReachabilityReportWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;" Usage="iNetworkWatchersOperations.GetAzureReachabilityReportWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-224">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-224">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-225">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-225">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-226">Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="54107-226">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-227">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-227">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-228">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-229">Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.</span><span class="sxs-lookup"><span data-stu-id="54107-229">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-230">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-230">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-231">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-231">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-232">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-232">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; GetFlowLogStatusWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; GetFlowLogStatusWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetFlowLogStatusWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFlowLogStatusWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.GetFlowLogStatusWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-233">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-233">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-234">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-234">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-235">Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-235">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-236">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-236">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-237">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-238">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="54107-238">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-239">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-239">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-240">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-240">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-241">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-241">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; GetNextHopWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt; GetNextHopWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetNextHopWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetNextHopWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetNextHopWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-242">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-242">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-243">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-243">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-244">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-244">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-245">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-245">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-246">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-247">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="54107-247">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-248">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-248">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-249">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-249">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-250">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-250">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;&gt; GetTopologyWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.Topology&gt;&gt; GetTopologyWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetTopologyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTopologyWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;&gt;" Usage="iNetworkWatchersOperations.GetTopologyWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-251">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-251">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-252">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-252">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-253">Parameter, die die Darstellung von Topologie zu definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-253">Parameters that define the representation of topology.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-254">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-254">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-255">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-256">Ruft die aktuelle Netzwerktopologie von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="54107-256">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-257">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-258">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-259">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-259">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingResultWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingResultWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetTroubleshootingResultWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTroubleshootingResultWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetTroubleshootingResultWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-260">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-260">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-261">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-261">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-262">Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-262">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-263">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-263">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-264">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-265">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="54107-265">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-266">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-266">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-267">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-267">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-268">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-268">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt; GetTroubleshootingWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetTroubleshootingWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTroubleshootingWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetTroubleshootingWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-269">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-269">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-270">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-270">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-271">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-271">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-272">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-272">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-273">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-274">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="54107-274">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-275">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-275">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-276">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-276">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-277">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-277">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; GetVMSecurityRulesWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt; GetVMSecurityRulesWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetVMSecurityRulesWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetVMSecurityRulesWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;" Usage="iNetworkWatchersOperations.GetVMSecurityRulesWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-278">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-278">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-279">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-279">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-280">Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-280">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-281">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-281">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-282">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-282">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-283">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="54107-283">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-284">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-284">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-285">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-285">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-286">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-286">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="iNetworkWatchersOperations.GetWithHttpMessagesAsync (resourceGroupName, networkWatcherName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-287">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-287">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-288">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-288">The name of the network watcher.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-289">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-289">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-290">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-291">Ruft die angegebene Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="54107-291">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-292">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-292">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-293">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-293">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-294">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-294">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListAllWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListAllWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.ListAllWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;" Usage="iNetworkWatchersOperations.ListAllWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="54107-295">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-295">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-296">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-296">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-297">Ruft alle Netzwerk-Watcher nach Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="54107-297">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-298">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-298">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-299">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-299">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-300">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-300">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProvidersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; ListAvailableProvidersWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt; ListAvailableProvidersWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.ListAvailableProvidersWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAvailableProvidersWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;" Usage="iNetworkWatchersOperations.ListAvailableProvidersWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-301">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-301">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-302">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-302">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-303">Parameter, die die Liste der verfügbaren Anbieter Bereich.</span><span class="sxs-lookup"><span data-stu-id="54107-303">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-304">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-304">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-305">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-305">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-306">Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.</span><span class="sxs-lookup"><span data-stu-id="54107-306">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-307">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-307">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-308">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-308">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-309">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-309">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;" Usage="iNetworkWatchersOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-310">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-310">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-311">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-311">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-312">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-312">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-313">Ruft alle Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="54107-313">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-314">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-314">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-315">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-315">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-316">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-316">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; SetFlowLogConfigurationWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt; SetFlowLogConfigurationWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.SetFlowLogConfigurationWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetFlowLogConfigurationWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;" Usage="iNetworkWatchersOperations.SetFlowLogConfigurationWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-317">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-317">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-318">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="54107-318">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-319">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-319">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-320">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-320">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-321">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-322">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="54107-322">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-323">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-323">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-324">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-324">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-325">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-325">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; UpdateTagsWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; UpdateTagsWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.UpdateTagsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTagsWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="iNetworkWatchersOperations.UpdateTagsWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-326">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-326">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-327">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-327">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-328">Der Parameter angegeben wird, um die Netzwerk-Watcher-Tags zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-328">Parameters supplied to update network watcher tags.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-329">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-329">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-330">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-331">Aktualisiert eine Netzwerk-Watcher-Tags.</span><span class="sxs-lookup"><span data-stu-id="54107-331">Updates a network watcher tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-332">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-332">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-333">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-333">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-334">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-334">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; VerifyIPFlowWithHttpMessagesAsync (string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt; VerifyIPFlowWithHttpMessagesAsync(string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.INetworkWatchersOperations.VerifyIPFlowWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyIPFlowWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;" Usage="iNetworkWatchersOperations.VerifyIPFlowWithHttpMessagesAsync (resourceGroupName, networkWatcherName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54107-335">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="54107-335">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="54107-336">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="54107-336">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54107-337">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="54107-337">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54107-338">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54107-338">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54107-339">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="54107-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54107-340">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="54107-340">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54107-341">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="54107-341">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54107-342">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="54107-342">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54107-343">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="54107-343">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>