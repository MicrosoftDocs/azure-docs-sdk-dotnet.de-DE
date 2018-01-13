<Type Name="DatabasesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabasesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabasesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabasesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabasesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fdfbb-101">Erweiterungsmethoden für DatabasesOperations.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-101">Extension methods for DatabasesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-105">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-105">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-106">Der Name der Azure SQL-Datenbank verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="fdfbb-106">The name of the Azure SQL database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fdfbb-107">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-107">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-109">Eine neue Azure SQL-Datenbank erstellt oder aktualisiert eine vorhandene Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-109">Creates a new Azure SQL database or updates an existing Azure SQL database.</span></span>
            <span data-ttu-id="fdfbb-110">Speicherort ist eine erforderliche Eigenschaft im Anforderungstext und und den Speicherort des SQL Servers identisch sein.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-110">Location is a required property in the request body, and it must be the same as the location of the SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverReplicationLinkAllowDataLossAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverReplicationLinkAllowDataLossAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAllowDataLossAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverReplicationLinkAllowDataLossAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginFailoverReplicationLinkAllowDataLossAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-112">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-113">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-114">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-114">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-115">Der Name der Azure SQL-Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-115">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fdfbb-116">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-116">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-118">Erzwingen Sie Failover der SQL Azure-datenbankreplikationslink mit der angegebenen ID, was möglicherweise zu Datenverlust führt.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-118">Force failover the Azure SQL database replication link with the given ID which may result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginFailoverReplicationLinkAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-120">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-120">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-121">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-121">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-122">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-122">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-123">Der Name der Azure SQL-Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-123">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fdfbb-124">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-124">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-126">Failover des Replikationslinks der Azure SQL-Datenbank mit der angegebenen ID.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-126">Failover the Azure SQL database replication link with the given ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPauseDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPauseDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPauseDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginPauseDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPauseDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginPauseDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginPauseDataWarehouseAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-128">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-128">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-129">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-129">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-130">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-130">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-131">Der Name des Azure SQL Data Warehouse-Datenbank angehalten.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-131">The name of the Azure SQL Data Warehouse database to pause.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-133">Anhalten einer Azure SQL Data Warehouse-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-133">Pause an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginResumeDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginResumeDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginResumeDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginResumeDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginResumeDataWarehouseAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-135">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-136">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-137">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-137">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-138">Der Name des Azure SQL Data Warehouse-Datenbank fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-138">The name of the Azure SQL Data Warehouse database to resume.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-140">Fortsetzen einer Azure SQL Data Warehouse-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-140">Resume an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-142">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-142">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-143">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-143">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-144">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-144">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-145">Der Name der Azure SQL-Datenbank verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="fdfbb-145">The name of the Azure SQL database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fdfbb-146">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-146">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-148">Eine neue Azure SQL-Datenbank erstellt oder aktualisiert eine vorhandene Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-148">Creates a new Azure SQL database or updates an existing Azure SQL database.</span></span>
            <span data-ttu-id="fdfbb-149">Speicherort ist eine erforderliche Eigenschaft im Anforderungstext und und den Speicherort des SQL Servers identisch sein.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-149">Location is a required property in the request body, and it must be the same as the location of the SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateTransparentDataEncryptionConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; CreateOrUpdateTransparentDataEncryptionConfigurationAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; CreateOrUpdateTransparentDataEncryptionConfigurationAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateTransparentDataEncryptionConfigurationAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateTransparentDataEncryptionConfigurationAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateTransparentDataEncryptionConfigurationAsync (operations, resourceGroupName, serverName, databaseName, status, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;CreateOrUpdateTransparentDataEncryptionConfigurationAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-151">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-151">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-152">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-152">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-153">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-153">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-154">Der Name der Azure SQL-Datenbank, die für die Einstellung der Transparent Data Encryption bezieht.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-154">The name of the Azure SQL database for which setting the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="status">
            <span data-ttu-id="fdfbb-155">Der Status der Azure SQL-Datenbank Transparent Data Encryption.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-155">The status of the Azure SQL Database Transparent Data Encryption.</span></span> <span data-ttu-id="fdfbb-156">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="fdfbb-156">Possible values include: 'Enabled', 'Disabled'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-158">Erstellt oder aktualisiert ein Azure SQL-Datenbank Transparent Datenverschlüsselungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-158">Creates or updates an Azure SQL Database Transparent Data Encryption Operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-160">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-160">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-161">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-161">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-162">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-162">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-163">Der Name der Azure SQL-Datenbank gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-163">The name of the Azure SQL database to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-165">Löscht eine Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-165">Deletes an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;DeleteReplicationLinkAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-167">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-168">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-169">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-169">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-170">Der Name der Azure SQL-Datenbank, die über den Replikationslink zu löschenden verfügt.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-170">The name of the Azure SQL database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fdfbb-171">Die ID des Replikationslinks gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-171">The ID of the replication link to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-173">Löscht die datenbankreplikationslinks SQL Azure mit der angegebenen ID.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-173">Deletes the Azure SQL database replication link with the given ID.</span></span> <span data-ttu-id="fdfbb-174">Kann nicht während eines Failovers verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-174">Cannot be done during failover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverReplicationLinkAllowDataLossAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverReplicationLinkAllowDataLossAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAllowDataLossAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverReplicationLinkAllowDataLossAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;FailoverReplicationLinkAllowDataLossAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-176">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-177">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-178">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-178">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-179">Der Name der Azure SQL-Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-179">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fdfbb-180">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-180">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-182">Erzwingen Sie Failover der SQL Azure-datenbankreplikationslink mit der angegebenen ID, was möglicherweise zu Datenverlust führt.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-182">Force failover the Azure SQL database replication link with the given ID which may result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;FailoverReplicationLinkAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-184">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-184">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-185">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-185">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-186">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-186">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-187">Der Name der Azure SQL-Datenbank, die über den Replikationslink Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-187">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fdfbb-188">Die ID des Replikationslinks Failover ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-188">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-190">Failover des Replikationslinks der Azure SQL-Datenbank mit der angegebenen ID.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-190">Failover the Azure SQL database replication link with the given ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-192">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-192">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-193">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-193">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-194">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-194">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-195">Der Name der Azure SQL-Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-195">The name of the Azure SQL database to be retrieved.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="fdfbb-196">Die kommagetrennten Liste von untergeordneten Objekten in der Antwort zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-196">The comma separated list of child objects to expand in the response.</span></span>
            <span data-ttu-id="fdfbb-197">Möglichen Eigenschaften: ServiceTierAdvisors, UpgradeHint, TransparentDataEncryption.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-197">Possible properties: serviceTierAdvisors, upgradeHint, transparentDataEncryption.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-199">Ruft Informationen zu einer Azure SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-199">Gets information about an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt; GetReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt; GetReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetReplicationLinkAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-201">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-201">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-202">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-202">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-203">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-203">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-204">Der Name der Azure SQL-Datenbank auf den Link, um zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-204">The name of the Azure SQL database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fdfbb-205">Die Replikation-Link-ID abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-205">The replication link ID to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-207">Ruft Informationen zu einer Azure SQL-datenbankreplikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-207">Gets information about an Azure SQL database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTierAdvisorAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; GetServiceTierAdvisorAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; GetServiceTierAdvisorAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetServiceTierAdvisorAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetServiceTierAdvisorAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetServiceTierAdvisorAsync (operations, resourceGroupName, serverName, databaseName, serviceTierAdvisorName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetServiceTierAdvisorAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-209">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-209">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-210">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-210">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-211">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-211">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-212">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-212">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="fdfbb-213">Der Name des dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-213">The name of service tier advisor.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-214">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-215">Ruft Informationen zu einem dienstebenenratgeber ab.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-215">Gets information about a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransparentDataEncryptionConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; GetTransparentDataEncryptionConfigurationAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; GetTransparentDataEncryptionConfigurationAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetTransparentDataEncryptionConfigurationAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTransparentDataEncryptionConfigurationAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetTransparentDataEncryptionConfigurationAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetTransparentDataEncryptionConfigurationAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-217">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-217">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-218">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-218">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-219">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-219">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-220">Der Name der Azure SQL-Datenbank, die für die transparente datenverschlüsselung bezieht.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-220">The name of the Azure SQL database for which the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-222">Ruft eine Azure SQL-Datenbank Transparent Data Encryption-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-222">Gets an Azure SQL Database Transparent Data Encryption Response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListByServerAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-224">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-224">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-225">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-225">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-226">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-226">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-228">Gibt Informationen zu einer Azure SQL-Datenbank zurück.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-228">Returns information about an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListReplicationLinksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; ListReplicationLinksAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; ListReplicationLinksAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListReplicationLinksAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListReplicationLinksAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListReplicationLinksAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListReplicationLinksAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-230">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-230">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-231">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-231">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-232">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-232">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-233">Der Name des abzurufenden Links für die Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-233">The name of the Azure SQL database to retrieve links for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-234">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-235">Ruft Informationen zu Replikationslinks für Azure SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-235">Gets information about Azure SQL database replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRestorePointsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt; ListRestorePointsAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt; ListRestorePointsAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListRestorePointsAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRestorePointsAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListRestorePointsAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListRestorePointsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-237">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-237">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-238">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-238">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-239">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-239">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-240">Wiederherstellungspunkte für der Namen der Azure SQL-Datenbank aus der verfügbaren abgerufen.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-240">The name of the Azure SQL database from which to retrieve available restore points.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-241">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-242">Gibt eine Liste der Azure SQL-Datenbank-Wiederherstellungspunkte.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-242">Returns a list of Azure SQL database restore points.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceTierAdvisorsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; ListServiceTierAdvisorsAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; ListServiceTierAdvisorsAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListServiceTierAdvisorsAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceTierAdvisorsAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListServiceTierAdvisorsAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListServiceTierAdvisorsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-244">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-244">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-245">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-245">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-246">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-246">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-247">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-247">The name of database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-248">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-248">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-249">Gibt Informationen zu Service Tier Ratgeber für die angegebene Datenbank zurück.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-249">Returns information about service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTransparentDataEncryptionActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt; ListTransparentDataEncryptionActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt; ListTransparentDataEncryptionActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListTransparentDataEncryptionActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTransparentDataEncryptionActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListTransparentDataEncryptionActivityAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListTransparentDataEncryptionActivityAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-250">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-250">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-251">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-251">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-252">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-252">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-253">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-253">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-254">Der Name der Azure SQL-Datenbank, die für die transparente datenverschlüsselung bezieht.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-254">The name of the Azure SQL database for which the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-255">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-256">Gibt eine Azure SQL-Datenbank Transparent Data Encryption Aktivität Antwort zurück.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-256">Returns an Azure SQL Database Transparent Data Encryption Activity Response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListUsagesAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-257">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-257">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-258">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-258">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-259">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-259">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-260">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-260">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-261">Der Name der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-261">The name of the Azure SQL database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-262">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-263">Informationen zur Verwendung der Azure SQL-Datenbank zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-263">Returns information about Azure SQL database usages.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PauseDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PauseDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PauseDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.PauseDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PauseDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.PauseDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;PauseDataWarehouseAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-264">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-264">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-265">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-265">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-266">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-266">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-267">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-267">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-268">Der Name des Azure SQL Data Warehouse-Datenbank angehalten.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-268">The name of the Azure SQL Data Warehouse database to pause.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-269">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-270">Anhalten einer Azure SQL Data Warehouse-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-270">Pause an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResumeDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResumeDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ResumeDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ResumeDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ResumeDataWarehouseAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fdfbb-271">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdfbb-272">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-272">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fdfbb-273">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-273">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fdfbb-274">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-274">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fdfbb-275">Der Name des Azure SQL Data Warehouse-Datenbank fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-275">The name of the Azure SQL Data Warehouse database to resume.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdfbb-276">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdfbb-277">Fortsetzen einer Azure SQL Data Warehouse-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fdfbb-277">Resume an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>