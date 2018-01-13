<Type Name="ReplicationLinksOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ReplicationLinksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ReplicationLinksOperationsExtensions = class" />
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
            <span data-ttu-id="eab51-101">Erweiterungsmethoden für ReplicationLinksOperations.</span><span class="sxs-lookup"><span data-stu-id="eab51-101">Extension methods for ReplicationLinksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginFailover">
      <MemberSignature Language="C#" Value="public static void BeginFailover (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailover(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailover(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailover (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailover : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailover (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-106">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-106">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-107">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-107">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-108">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-108">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static void BeginFailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailoverAllowDataLoss (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLoss (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-113">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-113">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-114">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-114">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-115">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-115">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="eab51-116">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="eab51-116">This operation might result in data loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;BeginFailoverAllowDataLossAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-121">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-121">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-122">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-122">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eab51-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eab51-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-124">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-124">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="eab51-125">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="eab51-125">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;BeginFailoverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-127">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-127">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-128">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-129">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-129">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-130">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-130">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-131">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-131">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eab51-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eab51-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-133">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-133">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-135">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-136">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-137">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-137">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-138">Der Name der Datenbank, die über den Replikationslink gelöscht werden sollen.</span><span class="sxs-lookup"><span data-stu-id="eab51-138">The name of the database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-139">Die ID des Replikationslinks gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="eab51-139">The ID of the replication link to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-140">Löscht einen Datenbankreplikationslink.</span><span class="sxs-lookup"><span data-stu-id="eab51-140">Deletes a database replication link.</span></span> <span data-ttu-id="eab51-141">Kann nicht während eines Failovers verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-141">Cannot be done during failover.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-143">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-143">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-144">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-144">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-145">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-145">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-146">Der Name der Datenbank, die über den Replikationslink gelöscht werden sollen.</span><span class="sxs-lookup"><span data-stu-id="eab51-146">The name of the database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-147">Die ID des Replikationslinks gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="eab51-147">The ID of the replication link to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eab51-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eab51-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-149">Löscht einen Datenbankreplikationslink.</span><span class="sxs-lookup"><span data-stu-id="eab51-149">Deletes a database replication link.</span></span> <span data-ttu-id="eab51-150">Kann nicht während eines Failovers verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-150">Cannot be done during failover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public static void Failover (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Failover(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Failover(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Failover (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member Failover : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Failover (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-152">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-153">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-154">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-154">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-155">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-155">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-156">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-156">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-157">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-157">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static void FailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void FailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub FailoverAllowDataLoss (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member FailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLoss (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-159">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-160">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-161">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-161">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-162">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-162">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-163">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-163">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-164">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-164">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="eab51-165">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="eab51-165">This operation might result in data loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;FailoverAllowDataLossAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-167">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-168">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-169">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-169">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-170">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-170">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-171">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-171">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eab51-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eab51-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-173">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-173">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="eab51-174">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="eab51-174">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;FailoverAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-176">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-177">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-178">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-178">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-179">Der Name der Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-179">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-180">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="eab51-180">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eab51-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eab51-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-182">Legt fest, welche Replikatdatenbank als primäre Replikatdatenbank verwendet wird, indem ein Failover von der aktuellen primären Replikatdatenbank durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="eab51-182">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ReplicationLink Get (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ReplicationLink Get(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String) As ReplicationLink" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ReplicationLink" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ReplicationLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-184">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-184">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-185">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-185">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-186">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-186">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-187">Der Name der Datenbank auf den Link, um zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="eab51-187">The name of the database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-188">Die Replikation-Link-ID abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="eab51-188">The replication link ID to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-189">Ruft ein datenbankreplikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="eab51-189">Gets a database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; GetAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; GetAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-191">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-191">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-192">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-192">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-193">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-193">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-194">Der Name der Datenbank auf den Link, um zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="eab51-194">The name of the database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="eab51-195">Die Replikation-Link-ID abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="eab51-195">The replication link ID to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eab51-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eab51-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-197">Ruft ein datenbankreplikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="eab51-197">Gets a database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of ReplicationLink)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-199">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-199">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-200">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-200">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-201">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-201">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-202">Der Name des abzurufenden Links für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="eab51-202">The name of the database to retrieve links for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-203">Listet eine datenbankreplikationslinks.</span><span class="sxs-lookup"><span data-stu-id="eab51-203">Lists a database's replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eab51-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="eab51-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eab51-205">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="eab51-205">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eab51-206">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="eab51-206">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eab51-207">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="eab51-207">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="eab51-208">Der Name des abzurufenden Links für die Datenbank.</span><span class="sxs-lookup"><span data-stu-id="eab51-208">The name of the database to retrieve links for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eab51-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eab51-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eab51-210">Listet eine datenbankreplikationslinks.</span><span class="sxs-lookup"><span data-stu-id="eab51-210">Lists a database's replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>