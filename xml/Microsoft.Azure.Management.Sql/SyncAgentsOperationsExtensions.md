<Type Name="SyncAgentsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SyncAgentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SyncAgentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SyncAgentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SyncAgentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="12fc5-101">Erweiterungsmethoden für SyncAgentsOperations.</span><span class="sxs-lookup"><span data-stu-id="12fc5-101">Extension methods for SyncAgentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncAgent BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, Microsoft.Azure.Management.Sql.Models.SyncAgent parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncAgent BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, class Microsoft.Azure.Management.Sql.Models.SyncAgent parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncAgent)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String, syncAgentName As String, parameters As SyncAgent) As SyncAgent" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncAgent -&gt; Microsoft.Azure.Management.Sql.Models.SyncAgent" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, syncAgentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncAgent</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncAgent" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-105">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-105">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-106">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-106">The name of the sync agent.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12fc5-107">Der Status der angeforderten Sync-Agent-Ressource.</span><span class="sxs-lookup"><span data-stu-id="12fc5-107">The requested sync agent resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-108">Erstellt oder aktualisiert einen Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-108">Creates or updates a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, Microsoft.Azure.Management.Sql.Models.SyncAgent parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, class Microsoft.Azure.Management.Sql.Models.SyncAgent parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncAgent,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncAgent * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, syncAgentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncAgent" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-112">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-112">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-113">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-113">The name of the sync agent.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12fc5-114">Der Status der angeforderten Sync-Agent-Ressource.</span><span class="sxs-lookup"><span data-stu-id="12fc5-114">The requested sync agent resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-116">Erstellt oder aktualisiert einen Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-116">Creates or updates a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String, syncAgentName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, syncAgentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-120">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-120">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-121">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-121">The name of the sync agent.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-122">Löscht einen clientsynchronisierungs-Agent an.</span><span class="sxs-lookup"><span data-stu-id="12fc5-122">Deletes a sync agent.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, syncAgentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-126">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-126">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-127">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-127">The name of the sync agent.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-129">Löscht einen clientsynchronisierungs-Agent an.</span><span class="sxs-lookup"><span data-stu-id="12fc5-129">Deletes a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncAgent CreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, Microsoft.Azure.Management.Sql.Models.SyncAgent parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncAgent CreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, class Microsoft.Azure.Management.Sql.Models.SyncAgent parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncAgent)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String, syncAgentName As String, parameters As SyncAgent) As SyncAgent" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncAgent -&gt; Microsoft.Azure.Management.Sql.Models.SyncAgent" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, syncAgentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncAgent</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncAgent" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-131">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-132">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-133">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-133">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-134">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-134">The name of the sync agent.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12fc5-135">Der Status der angeforderten Sync-Agent-Ressource.</span><span class="sxs-lookup"><span data-stu-id="12fc5-135">The requested sync agent resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-136">Erstellt oder aktualisiert einen Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-136">Creates or updates a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, Microsoft.Azure.Management.Sql.Models.SyncAgent parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, class Microsoft.Azure.Management.Sql.Models.SyncAgent parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncAgent,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncAgent * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, syncAgentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncAgent" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-138">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-138">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-139">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-139">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-140">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-140">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-141">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-141">The name of the sync agent.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12fc5-142">Der Status der angeforderten Sync-Agent-Ressource.</span><span class="sxs-lookup"><span data-stu-id="12fc5-142">The requested sync agent resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-144">Erstellt oder aktualisiert einen Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-144">Creates or updates a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String, syncAgentName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.Delete (operations, resourceGroupName, serverName, syncAgentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-146">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-146">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-147">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-147">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-148">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-148">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-149">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-149">The name of the sync agent.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-150">Löscht einen clientsynchronisierungs-Agent an.</span><span class="sxs-lookup"><span data-stu-id="12fc5-150">Deletes a sync agent.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, syncAgentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-152">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-153">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-154">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-154">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-155">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-155">The name of the sync agent.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-157">Löscht einen clientsynchronisierungs-Agent an.</span><span class="sxs-lookup"><span data-stu-id="12fc5-157">Deletes a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties GenerateKey (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties GenerateKey(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.GenerateKey(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateKey (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String, syncAgentName As String) As SyncAgentKeyProperties" />
      <MemberSignature Language="F#" Value="static member GenerateKey : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.GenerateKey (operations, resourceGroupName, serverName, syncAgentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-159">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-160">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-161">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-161">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-162">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-162">The name of the sync agent.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-163">Generiert einen Sync-Agent-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="12fc5-163">Generates a sync agent key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties&gt; GenerateKeyAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties&gt; GenerateKeyAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.GenerateKeyAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateKeyAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.GenerateKeyAsync (operations, resourceGroupName, serverName, syncAgentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;GenerateKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentKeyProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-165">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-166">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-167">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-167">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-168">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-168">The name of the sync agent.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-170">Generiert einen Sync-Agent-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="12fc5-170">Generates a sync agent key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncAgent Get (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncAgent Get(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String, syncAgentName As String) As SyncAgent" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncAgent" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.Get (operations, resourceGroupName, serverName, syncAgentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncAgent</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-172">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-172">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-173">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-173">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-174">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-174">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-175">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-175">The name of the sync agent.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-176">Ruft einen clientsynchronisierungs-Agent ab.</span><span class="sxs-lookup"><span data-stu-id="12fc5-176">Gets a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; GetAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; GetAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, syncAgentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-178">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-178">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-179">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-179">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-180">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-180">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-181">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-181">The name of the sync agent.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-183">Ruft einen clientsynchronisierungs-Agent ab.</span><span class="sxs-lookup"><span data-stu-id="12fc5-183">Gets a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; ListByServer (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; ListByServer(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String) As IPage(Of SyncAgent)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-185">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-185">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-186">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-186">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-187">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-187">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-188">Listen Agents auf einem Server zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="12fc5-188">Lists sync agents in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;ListByServerAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-190">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-190">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-191">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-191">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-192">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-192">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-194">Listen Agents auf einem Server zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="12fc5-194">Lists sync agents in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgent&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As ISyncAgentsOperations, nextPageLink As String) As IPage(Of SyncAgent)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="12fc5-196">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="12fc5-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-197">Listen Agents auf einem Server zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="12fc5-197">Lists sync agents in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;ListByServerNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgent&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="12fc5-199">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="12fc5-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-201">Listen Agents auf einem Server zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="12fc5-201">Lists sync agents in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkedDatabases">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt; ListLinkedDatabases (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt; ListLinkedDatabases(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabases(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLinkedDatabases (operations As ISyncAgentsOperations, resourceGroupName As String, serverName As String, syncAgentName As String) As IPage(Of SyncAgentLinkedDatabase)" />
      <MemberSignature Language="F#" Value="static member ListLinkedDatabases : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabases (operations, resourceGroupName, serverName, syncAgentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-203">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-203">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-204">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-204">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-205">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-205">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-206">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-206">The name of the sync agent.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-207">Listen von Datenbanken mit einem Synchronisierungs-Agent verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="12fc5-207">Lists databases linked to a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkedDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt; ListLinkedDatabasesAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt; ListLinkedDatabasesAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string resourceGroupName, string serverName, string syncAgentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabasesAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLinkedDatabasesAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabasesAsync (operations, resourceGroupName, serverName, syncAgentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;ListLinkedDatabasesAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="12fc5-209">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="12fc5-209">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="12fc5-210">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="12fc5-210">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="12fc5-211">Der Name des Servers, auf dem der Synchronisierungs-Agent gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="12fc5-211">The name of the server on which the sync agent is hosted.</span></span>
            </param>
        <param name="syncAgentName">
            <span data-ttu-id="12fc5-212">Der Name des Synchronisierungs-Agent.</span><span class="sxs-lookup"><span data-stu-id="12fc5-212">The name of the sync agent.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-213">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-214">Listen von Datenbanken mit einem Synchronisierungs-Agent verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="12fc5-214">Lists databases linked to a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkedDatabasesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt; ListLinkedDatabasesNext (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt; ListLinkedDatabasesNext(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabasesNext(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLinkedDatabasesNext (operations As ISyncAgentsOperations, nextPageLink As String) As IPage(Of SyncAgentLinkedDatabase)" />
      <MemberSignature Language="F#" Value="static member ListLinkedDatabasesNext : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabasesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="12fc5-216">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="12fc5-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-217">Listen von Datenbanken mit einem Synchronisierungs-Agent verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="12fc5-217">Lists databases linked to a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkedDatabasesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt; ListLinkedDatabasesNextAsync (this Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt; ListLinkedDatabasesNextAsync(class Microsoft.Azure.Management.Sql.ISyncAgentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabasesNextAsync(Microsoft.Azure.Management.Sql.ISyncAgentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLinkedDatabasesNextAsync : Microsoft.Azure.Management.Sql.ISyncAgentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions.ListLinkedDatabasesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncAgentsOperationsExtensions/&lt;ListLinkedDatabasesNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncAgentLinkedDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncAgentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="12fc5-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="12fc5-218">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="12fc5-219">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="12fc5-219">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12fc5-220">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12fc5-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12fc5-221">Listen von Datenbanken mit einem Synchronisierungs-Agent verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="12fc5-221">Lists databases linked to a sync agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>