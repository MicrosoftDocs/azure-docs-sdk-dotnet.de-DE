<Type Name="NetworkWatchersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkWatchersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkWatchersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6f398-101">Erweiterungsmethoden für NetworkWatchersOperations.</span><span class="sxs-lookup"><span data-stu-id="6f398-101">Extension methods for NetworkWatchersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; BeginCheckConnectivityAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; BeginCheckConnectivityAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivityAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginCheckConnectivityAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="networkWatcherName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-103">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-104">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-104">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-106">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-106">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginGetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginGetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatusAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetFlowLogStatusAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-108">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-108">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-109">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-109">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="6f398-110">Die Zielressource, den Datenfluss Anmeldestatus abrufen.</span><span class="sxs-lookup"><span data-stu-id="6f398-110">The target resource where getting the flow logging status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-112">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-112">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; BeginGetNextHopAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; BeginGetNextHopAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHopAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetNextHopAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-114">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-115">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-115">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-116">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-116">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-118">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-118">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-120">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-121">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-121">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-122">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-122">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-124">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="6f398-124">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingResultAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-126">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-126">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-127">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-127">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="6f398-128">Führen zum Abfragen der Fehlerbehebung die Zielressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="6f398-128">The target resource ID to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-130">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="6f398-130">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; BeginGetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; BeginGetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetVMSecurityRulesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-132">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-132">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-133">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-133">The name of the network watcher.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="6f398-134">Die ID des Ziels VM.</span><span class="sxs-lookup"><span data-stu-id="6f398-134">ID of the target VM.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-136">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-136">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginSetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginSetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginSetFlowLogConfigurationAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-138">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-138">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-139">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-139">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-140">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-140">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-142">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-142">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; BeginVerifyIPFlowAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; BeginVerifyIPFlowAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlowAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginVerifyIPFlowAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-144">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-144">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-145">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-145">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-146">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-146">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-148">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="6f398-148">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; CheckConnectivityAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; CheckConnectivityAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CheckConnectivityAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckConnectivityAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;CheckConnectivityAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="networkWatcherName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-150">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-150">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-151">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-151">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-152">Parameter, die die Watcher-Netzwerkressource definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-152">Parameters that define the network watcher resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-154">Erstellt oder aktualisiert eine netzwerküberwachung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-154">Creates or updates a network watcher in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-156">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-157">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-157">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-159">Löscht die angegebene Netzwerk-Watcher-Ressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-159">Deletes the specified network watcher resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-161">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-161">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-162">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-162">The name of the network watcher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-164">Ruft die angegebene Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-164">Gets the specified network watcher by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; GetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; GetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatusAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetFlowLogStatusAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-166">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-166">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-167">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-167">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="6f398-168">Die Zielressource, den Datenfluss Anmeldestatus abrufen.</span><span class="sxs-lookup"><span data-stu-id="6f398-168">The target resource where getting the flow logging status.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-170">Abfragen der Status des Flusses melden Sie sich eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-170">Queries status of flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; GetNextHopAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; GetNextHopAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetNextHopAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNextHopAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetNextHopAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-172">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-172">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-173">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-173">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-174">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-174">Parameters that define the source and destination endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-176">Ruft den nächsten Hop aus den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-176">Gets the next hop from the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt; GetTopologyAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt; GetTopologyAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTopologyAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTopologyAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTopologyAsync (operations, resourceGroupName, networkWatcherName, targetResourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTopologyAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-178">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-178">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-179">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-179">The name of the network watcher.</span></span>
            </param>
        <param name="targetResourceGroupName">
            <span data-ttu-id="6f398-180">Der Name der Zielressourcengruppe Topologie auf ausführen.</span><span class="sxs-lookup"><span data-stu-id="6f398-180">The name of the target resource group to perform topology on.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-182">Ruft die aktuelle Netzwerktopologie von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-182">Gets the current network topology by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-184">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-184">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-185">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-185">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-186">Parameter, die die Ressource zur Problembehandlung bei definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-186">Parameters that define the resource to troubleshoot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-188">Initiieren Sie die Problembehandlung wird für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="6f398-188">Initiate troubleshooting on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingResultAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-190">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-190">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-191">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-191">The name of the network watcher resource.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="6f398-192">Führen zum Abfragen der Fehlerbehebung die Zielressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="6f398-192">The target resource ID to query the troubleshooting result.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-194">Abrufen der letzten abgeschlossenen zur Problembehandlung Ergebnis für eine angegebene Ressource</span><span class="sxs-lookup"><span data-stu-id="6f398-194">Get the last completed troubleshooting result on a specified resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; GetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; GetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetVMSecurityRulesAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-196">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-196">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-197">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-197">The name of the network watcher.</span></span>
            </param>
        <param name="targetResourceId">
            <span data-ttu-id="6f398-198">Die ID des Ziels VM.</span><span class="sxs-lookup"><span data-stu-id="6f398-198">ID of the target VM.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-200">Ruft die Sicherheit konfiguriert und effektive Gruppenregeln auf den angegebenen virtuellen Computer ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-200">Gets the configured and effective security group rules on the specified VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;ListAllAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-201">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-202">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-203">Ruft alle Netzwerk-Watcher nach Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-203">Gets all network watchers by subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-205">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-205">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-207">Ruft alle Netzwerk-Watcher durch Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="6f398-207">Gets all network watchers by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; SetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; SetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;SetFlowLogConfigurationAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-209">Der Name der Ressourcengruppe, Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-209">The name of the network watcher resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-210">Der Name der Watcher Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-210">The name of the network watcher resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-211">Parameter, die die Konfiguration des Protokolls für Datenfluss zu definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-211">Parameters that define the configuration of flow log.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-213">Konfiguriert Flow-Protokoll für eine angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="6f398-213">Configures flow log on a specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; VerifyIPFlowAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; VerifyIPFlowAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlowAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;VerifyIPFlowAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6f398-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6f398-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6f398-215">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6f398-215">The name of the resource group.</span></span>
            </param>
        <param name="networkWatcherName">
            <span data-ttu-id="6f398-216">Der Name des Netzwerk-Watcher.</span><span class="sxs-lookup"><span data-stu-id="6f398-216">The name of the network watcher.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6f398-217">Parameter, die den IP-Nachrichtenfluss zu prüfende definieren.</span><span class="sxs-lookup"><span data-stu-id="6f398-217">Parameters that define the IP flow to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6f398-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6f398-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6f398-219">Überprüfen Sie die IP-Datenfluss von den angegebenen virtuellen Computer an einem Speicherort, die zurzeit konfigurierten NSG-Regeln angegeben.</span><span class="sxs-lookup"><span data-stu-id="6f398-219">Verify IP flow from the specified VM to a location given the currently configured NSG rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>