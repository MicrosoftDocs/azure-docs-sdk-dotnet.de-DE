<Type Name="NetworkWatchersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkWatchersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkWatchersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ec83d-101">Erweiterungsmethoden für NetworkWatchersOperations.</span><span class="sxs-lookup"><span data-stu-id="ec83d-101">Extension methods for NetworkWatchersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectivityInformation BeginCheckConnectivity (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectivityInformation BeginCheckConnectivity(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivity(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCheckConnectivity (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As ConnectivityParameters) As ConnectivityInformation" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivity : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivity (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivityInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-103">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-103">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-104">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-104">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-105">Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="ec83d-105">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-106">Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-106">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; BeginCheckConnectivityAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; BeginCheckConnectivityAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivityAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginCheckConnectivityAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-108">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-108">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-109">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-109">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-110">Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="ec83d-110">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-112">Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-112">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDelete (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-114">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-115">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-115">The name of the network watcher.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-116">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-116">Deletes the specified network watcher resource.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-118">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-119">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-119">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-121">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-121">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AzureReachabilityReport BeginGetAzureReachabilityReport (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport BeginGetAzureReachabilityReport(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReport(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetAzureReachabilityReport (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AzureReachabilityReportParameters) As AzureReachabilityReport" />
      <MemberSignature Language="F#" Value="static member BeginGetAzureReachabilityReport : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReport (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-123">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-123">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-124">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-124">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-125">Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-125">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-126">Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-126">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAzureReachabilityReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; BeginGetAzureReachabilityReportAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; BeginGetAzureReachabilityReportAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReportAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetAzureReachabilityReportAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetAzureReachabilityReportAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetAzureReachabilityReportAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-128">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-128">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-129">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-129">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-130">Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-130">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-132">Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-132">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginGetFlowLogStatus (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginGetFlowLogStatus(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatus(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetFlowLogStatus (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogStatusParameters) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatus : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatus (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-134">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-134">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-135">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-135">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-136">Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-136">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-137">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-137">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginGetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginGetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatusAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetFlowLogStatusAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-139">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-139">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-140">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-140">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-141">Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-141">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-143">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-143">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NextHopResult BeginGetNextHop (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NextHopResult BeginGetNextHop(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHop(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetNextHop (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NextHopParameters) As NextHopResult" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHop : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters -&gt; Microsoft.Azure.Management.Network.Models.NextHopResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHop (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NextHopResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-145">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-146">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-146">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-147">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-147">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-148">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-148">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt; BeginGetNextHopAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt; BeginGetNextHopAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHopAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetNextHopAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-150">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-150">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-151">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-151">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-152">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-152">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-154">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-154">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshooting">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshooting (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshooting(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshooting(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetTroubleshooting (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshooting : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshooting (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-156">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-157">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-157">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-158">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-158">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-159">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-159">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-161">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-161">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-162">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-162">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-163">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-163">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-165">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-165">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResult">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshootingResult (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult BeginGetTroubleshootingResult(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResult(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetTroubleshootingResult (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As QueryTroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResult : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResult (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-167">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-167">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-168">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-168">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-169">Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-169">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-170">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-170">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; BeginGetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingResultAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-172">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-172">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-173">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-173">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-174">Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-174">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-176">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-176">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult BeginGetVMSecurityRules (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult BeginGetVMSecurityRules(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRules(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetVMSecurityRules (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As SecurityGroupViewParameters) As SecurityGroupViewResult" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRules : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRules (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-178">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-178">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-179">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-179">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-180">Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-180">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-181">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-181">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; BeginGetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; BeginGetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginGetVMSecurityRulesAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-183">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-183">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-184">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-184">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-185">Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-185">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-187">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-187">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProviders">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AvailableProvidersList BeginListAvailableProviders (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AvailableProvidersList BeginListAvailableProviders(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProviders(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListAvailableProviders (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AvailableProvidersListParameters) As AvailableProvidersList" />
      <MemberSignature Language="F#" Value="static member BeginListAvailableProviders : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersList" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProviders (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AvailableProvidersList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-189">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-189">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-190">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-190">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-191">Parameter, die die Liste der verfügbaren Anbieter Bereich.</span><span class="sxs-lookup"><span data-stu-id="ec83d-191">Parameters that scope the list of available providers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-192">Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.</span><span class="sxs-lookup"><span data-stu-id="ec83d-192">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListAvailableProvidersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; BeginListAvailableProvidersAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; BeginListAvailableProvidersAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProvidersAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListAvailableProvidersAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginListAvailableProvidersAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginListAvailableProvidersAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-194">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-194">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-195">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-195">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-196">Parameter, die die Liste der verfügbaren Anbieter Bereich.</span><span class="sxs-lookup"><span data-stu-id="ec83d-196">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-197">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-198">Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.</span><span class="sxs-lookup"><span data-stu-id="ec83d-198">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginSetFlowLogConfiguration (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation BeginSetFlowLogConfiguration(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfiguration(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginSetFlowLogConfiguration (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogInformation) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfiguration : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfiguration (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-199">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-200">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-200">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-201">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-201">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-202">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-202">Parameters that define the configuration of flow log.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-203">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-203">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginSetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; BeginSetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginSetFlowLogConfigurationAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-205">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-205">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-206">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-206">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-207">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-207">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-209">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-209">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlow">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult BeginVerifyIPFlow (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult BeginVerifyIPFlow(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlow(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginVerifyIPFlow (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As VerificationIPFlowParameters) As VerificationIPFlowResult" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlow : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlow (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-211">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-211">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-212">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-212">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-213">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-213">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-214">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="ec83d-214">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; BeginVerifyIPFlowAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; BeginVerifyIPFlowAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlowAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;BeginVerifyIPFlowAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-216">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-216">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-217">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-217">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-218">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-218">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-220">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="ec83d-220">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectivityInformation CheckConnectivity (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectivityInformation CheckConnectivity(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivity(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckConnectivity (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As ConnectivityParameters) As ConnectivityInformation" />
      <MemberSignature Language="F#" Value="static member CheckConnectivity : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivity (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivityInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-222">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-222">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-223">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-223">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-224">Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="ec83d-224">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-225">Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-225">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; CheckConnectivityAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt; CheckConnectivityAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.ConnectivityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivityAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectivityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckConnectivityAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectivityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;CheckConnectivityAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectivityInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-227">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-227">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-228">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-228">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-229">Parameter, die bestimmen, wie die Konnektivität gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="ec83d-229">Parameters that determine how the connectivity check will be performed.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-230">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-231">Überprüft die Möglichkeit, eine direkte TCP-Verbindung von einem virtuellen Computer für einen gegebenen Endpunkt, z. B. einem anderen virtuellen Computer oder eine beliebige Remoteserver herstellen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-231">Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher CreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher CreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NetworkWatcher) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-233">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-233">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-234">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-234">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-235">Parameter, die die Watcher-Netzwerkressource definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-235">Parameters that define the network watcher resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-236">Erstellt oder aktualisiert eine netzwerküberwachung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-236">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NetworkWatcher parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkWatcher,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkWatcher * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkWatcher" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-237">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-237">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-238">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-238">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-239">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-239">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-240">Parameter, die die Watcher-Netzwerkressource definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-240">Parameters that define the network watcher resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-241">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-242">Erstellt oder aktualisiert eine netzwerküberwachung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-242">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Delete(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Delete (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-244">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-244">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-245">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-245">The name of the network watcher.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-246">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-246">Deletes the specified network watcher resource.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-248">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-248">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-249">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-249">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-250">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-250">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-251">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-251">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher Get (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher Get(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.Get (operations, resourceGroupName, networkWatcherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-253">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-253">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-254">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-254">The name of the network watcher.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-255">Ruft die angegebene Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-255">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-257">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-257">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-258">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-258">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-259">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-260">Ruft die angegebene Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-260">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReport">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AzureReachabilityReport GetAzureReachabilityReport (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport GetAzureReachabilityReport(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReport(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAzureReachabilityReport (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AzureReachabilityReportParameters) As AzureReachabilityReport" />
      <MemberSignature Language="F#" Value="static member GetAzureReachabilityReport : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReport (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-261">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-262">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-262">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-263">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-263">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-264">Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-264">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-265">Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-265">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAzureReachabilityReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; GetAzureReachabilityReportAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt; GetAzureReachabilityReportAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReportAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAzureReachabilityReportAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetAzureReachabilityReportAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetAzureReachabilityReportAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-266">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-266">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-267">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-267">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-268">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-268">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-269">Parameter, die Berichtskonfiguration für Azure Erreichbarkeit zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-269">Parameters that determine Azure reachability report configuration.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-270">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-270">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-271">Ruft die relative Latenz-Bewertung für Internet Dienstanbieter von einem bestimmten Speicherort auf Azure-Regionen.</span><span class="sxs-lookup"><span data-stu-id="ec83d-271">Gets the relative latency score for internet service providers from a specified location to Azure regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation GetFlowLogStatus (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation GetFlowLogStatus(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatus(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFlowLogStatus (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogStatusParameters) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatus : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatus (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-272">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-273">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-273">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-274">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-274">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-275">Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-275">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-276">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-276">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; GetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; GetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatusAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetFlowLogStatusAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-277">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-278">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-278">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-279">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-279">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-280">Parameter, die eine Ressource für Abfragestatus Flow-Protokoll zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-280">Parameters that define a resource to query flow log status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-281">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-281">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-282">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-282">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NextHopResult GetNextHop (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NextHopResult GetNextHop(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHop(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetNextHop (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As NextHopParameters) As NextHopResult" />
      <MemberSignature Language="F#" Value="static member GetNextHop : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters -&gt; Microsoft.Azure.Management.Network.Models.NextHopResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHop (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NextHopResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-283">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-284">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-284">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-285">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-285">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-286">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-286">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-287">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-287">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt; GetNextHopAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NextHopResult&gt; GetNextHopAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.NextHopParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHopAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NextHopParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNextHopAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.NextHopParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetNextHopAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NextHopResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NextHopParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-288">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-288">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-289">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-289">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-290">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-290">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-291">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-291">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-292">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-292">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-293">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-293">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopology">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.Topology GetTopology (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.Topology GetTopology(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopology(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTopology (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TopologyParameters) As Topology" />
      <MemberSignature Language="F#" Value="static member GetTopology : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters -&gt; Microsoft.Azure.Management.Network.Models.Topology" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopology (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Topology</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-294">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-294">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-295">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-295">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-296">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-296">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-297">Parameter, die die Darstellung von Topologie zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-297">Parameters that define the representation of topology.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-298">Ruft die aktuelle Netzwerktopologie von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-298">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt; GetTopologyAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.Topology&gt; GetTopologyAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TopologyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopologyAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TopologyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTopologyAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TopologyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTopologyAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTopologyAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.Topology&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TopologyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-299">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-299">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-300">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-300">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-301">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-301">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-302">Parameter, die die Darstellung von Topologie zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-302">Parameters that define the representation of topology.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-303">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-303">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-304">Ruft die aktuelle Netzwerktopologie von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-304">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshooting">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshooting (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshooting(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshooting(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTroubleshooting (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member GetTroubleshooting : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshooting (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-305">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-305">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-306">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-306">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-307">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-307">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-308">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-308">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-309">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-309">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-310">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-310">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-311">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-311">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-312">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-312">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-313">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-313">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-314">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-315">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-315">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResult">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshootingResult (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.TroubleshootingResult GetTroubleshootingResult(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResult(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTroubleshootingResult (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As QueryTroubleshootingParameters) As TroubleshootingResult" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResult : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResult (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.TroubleshootingResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-316">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-316">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-317">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-317">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-318">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-318">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-319">Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-319">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-320">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-320">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt; GetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingResultAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.QueryTroubleshootingParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-321">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-321">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-322">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-322">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-323">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-323">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-324">Führen Parameter, die die Ressource, um die Problembehandlung für Abfragen definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-324">Parameters that define the resource to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-325">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-325">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-326">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="ec83d-326">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult GetVMSecurityRules (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult GetVMSecurityRules(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRules(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVMSecurityRules (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As SecurityGroupViewParameters) As SecurityGroupViewResult" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRules : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRules (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-327">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-327">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-328">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-328">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-329">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-329">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-330">Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-330">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-331">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-331">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; GetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt; GetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;GetVMSecurityRulesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.SecurityGroupViewParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-332">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-332">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-333">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-333">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-334">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-334">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-335">Parameter, die den virtuellen Computer zum Überprüfen von Sicherheitsgruppen für definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-335">Parameters that define the VM to check security groups for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-336">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-336">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-337">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-337">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; List (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; List(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkWatchersOperations, resourceGroupName As String) As IEnumerable(Of NetworkWatcher)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-338">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-338">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-339">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-339">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-340">Ruft alle Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-340">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; ListAll (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; ListAll(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.INetworkWatchersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INetworkWatchersOperations) As IEnumerable(Of NetworkWatcher)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.INetworkWatchersOperations -&gt; seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-341">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-341">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-342">Ruft alle Netzwerk-Watcher nach Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-342">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAllAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-343">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-343">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-344">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-345">Ruft alle Netzwerk-Watcher nach Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-345">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-346">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-346">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-347">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-347">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-348">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-348">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-349">Ruft alle Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ec83d-349">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProviders">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.AvailableProvidersList ListAvailableProviders (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.AvailableProvidersList ListAvailableProviders(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProviders(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableProviders (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As AvailableProvidersListParameters) As AvailableProvidersList" />
      <MemberSignature Language="F#" Value="static member ListAvailableProviders : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersList" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProviders (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AvailableProvidersList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-350">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-350">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-351">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-351">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-352">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-352">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-353">Parameter, die die Liste der verfügbaren Anbieter Bereich.</span><span class="sxs-lookup"><span data-stu-id="ec83d-353">Parameters that scope the list of available providers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-354">Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.</span><span class="sxs-lookup"><span data-stu-id="ec83d-354">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableProvidersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; ListAvailableProvidersAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt; ListAvailableProvidersAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProvidersAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableProvidersAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.ListAvailableProvidersAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;ListAvailableProvidersAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.AvailableProvidersListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-355">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-355">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-356">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-356">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-357">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-357">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-358">Parameter, die die Liste der verfügbaren Anbieter Bereich.</span><span class="sxs-lookup"><span data-stu-id="ec83d-358">Parameters that scope the list of available providers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-359">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-359">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-360">Listet alle verfügbaren Internetdienstanbieter für einen angegebenen Azure-Region an.</span><span class="sxs-lookup"><span data-stu-id="ec83d-360">Lists all available internet service providers for a specified Azure region.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.FlowLogInformation SetFlowLogConfiguration (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.FlowLogInformation SetFlowLogConfiguration(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfiguration(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetFlowLogConfiguration (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As FlowLogInformation) As FlowLogInformation" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfiguration : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfiguration (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.FlowLogInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-361">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-361">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-362">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-362">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-363">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-363">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-364">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-364">Parameters that define the configuration of flow log.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-365">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-365">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; SetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt; SetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.FlowLogInformation parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.FlowLogInformation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.FlowLogInformation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;SetFlowLogConfigurationAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.FlowLogInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-366">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-366">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-367">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-367">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-368">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-368">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-369">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-369">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-370">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-370">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-371">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="ec83d-371">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkWatcher UpdateTags (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkWatcher UpdateTags(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As TagsObject) As NetworkWatcher" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkWatcher" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTags (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkWatcher</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-372">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-372">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-373">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-373">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-374">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-374">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-375">Der Parameter angegeben wird, um die Netzwerk-Watcher-Tags zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-375">Parameters supplied to update network watcher tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-376">Aktualisiert eine Netzwerk-Watcher-Tags.</span><span class="sxs-lookup"><span data-stu-id="ec83d-376">Updates a network watcher tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkWatcher&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-377">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-377">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-378">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-378">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-379">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-379">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-380">Der Parameter angegeben wird, um die Netzwerk-Watcher-Tags zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-380">Parameters supplied to update network watcher tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-381">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-382">Aktualisiert eine Netzwerk-Watcher-Tags.</span><span class="sxs-lookup"><span data-stu-id="ec83d-382">Updates a network watcher tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlow">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult VerifyIPFlow (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult VerifyIPFlow(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlow(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function VerifyIPFlow (operations As INetworkWatchersOperations, resourceGroupName As String, networkWatcherName As String, parameters As VerificationIPFlowParameters) As VerificationIPFlowResult" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlow : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlow (operations, resourceGroupName, networkWatcherName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-383">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-383">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-384">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-384">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-385">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-385">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-386">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-386">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-387">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="ec83d-387">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; VerifyIPFlowAsync (this Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt; VerifyIPFlowAsync(class Microsoft.Azure.Management.Network.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync(Microsoft.Azure.Management.Network.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlowAsync : Microsoft.Azure.Management.Network.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkWatchersOperationsExtensions/&lt;VerifyIPFlowAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ec83d-388">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ec83d-388">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ec83d-389">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ec83d-389">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="ec83d-390">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="ec83d-390">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec83d-391">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="ec83d-391">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec83d-392">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ec83d-392">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec83d-393">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="ec83d-393">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>