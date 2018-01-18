<Type Name="ElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolsOperationsExtensions = class" />
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
            <span data-ttu-id="a1b40-101">Erweiterungsmethoden für ElasticPoolsOperations.</span><span class="sxs-lookup"><span data-stu-id="a1b40-101">Extension methods for ElasticPoolsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-105">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-105">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-106">Der Name der SQL Azure elastischen Pool verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="a1b40-106">The name of the Azure SQL Elastic Pool to be operated on (Updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b40-107">Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="a1b40-107">The required parameters for creating or updating an Elastic Pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-109">Erstellt einen neuen elastischen Pool für SQL Azure oder aktualisiert einen vorhandenen elastischen Pool für SQL Azure.</span><span class="sxs-lookup"><span data-stu-id="a1b40-109">Creates a new Azure SQL elastic pool or updates an existing Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-111">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-112">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-113">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-113">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-114">Der Name der SQL Azure elastischen Pool verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="a1b40-114">The name of the Azure SQL Elastic Pool to be operated on (Updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b40-115">Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="a1b40-115">The required parameters for creating or updating an Elastic Pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-117">Erstellt einen neuen elastischen Pool für SQL Azure oder aktualisiert einen vorhandenen elastischen Pool für SQL Azure.</span><span class="sxs-lookup"><span data-stu-id="a1b40-117">Creates a new Azure SQL elastic pool or updates an existing Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-119">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-119">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-120">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-120">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-121">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-121">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-122">Der Name des SQL Azure elastischen Pools gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="a1b40-122">The name of the Azure SQL Elastic Pool to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-124">Löscht den elastischen Pool für SQL Azure.</span><span class="sxs-lookup"><span data-stu-id="a1b40-124">Deletes the Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-126">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-126">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-127">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-127">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-128">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-128">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-129">Der Name des SQL Azure elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a1b40-129">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-131">Ruft Informationen zu einem elastischen Pool für SQL Azure ab.</span><span class="sxs-lookup"><span data-stu-id="a1b40-131">Gets information about an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabaseAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabaseAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetDatabaseAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatabaseAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetDatabaseAsync (operations, resourceGroupName, serverName, elasticPoolName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;GetDatabaseAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-133">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-134">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-135">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-135">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-136">Der Name des SQL Azure elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a1b40-136">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b40-137">Der Name der Azure SQL-Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a1b40-137">The name of the Azure SQL database to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-139">Ruft Informationen zu einer Azure SQL-Datenbank in einem elastischen Pool für SQL Azure ab.</span><span class="sxs-lookup"><span data-stu-id="a1b40-139">Gets information about an Azure SQL database inside of an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt; ListActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt; ListActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListActivityAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListActivityAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-141">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-141">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-142">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-142">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-143">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-143">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-144">Der Name der SQL Azure elastischen Pool für das Abrufen der aktuellen Aktivität.</span><span class="sxs-lookup"><span data-stu-id="a1b40-144">The name of the Azure SQL Elastic Pool for which to get the current activity.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-146">Gibt Informationen zu SQL Azure elastischen Pool Aktivitäten zurück.</span><span class="sxs-lookup"><span data-stu-id="a1b40-146">Returns information about Azure SQL elastic pool activities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListByServerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-148">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-148">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-149">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-149">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-150">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-150">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-152">Gibt Informationen zu Azure SQL-elastische Pools.</span><span class="sxs-lookup"><span data-stu-id="a1b40-152">Returns information about Azure SQL elastic pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabaseActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt; ListDatabaseActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt; ListDatabaseActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabaseActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabaseActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabaseActivityAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListDatabaseActivityAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-154">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-154">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-155">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-155">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-156">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-156">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-157">Der Name des Azure SQL elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="a1b40-157">The name of the Azure SQL Elastic Pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-159">Informationen zur Aktivität zurückgegeben in Azure SQL-Datenbanken in einem elastischen Pool für SQL Azure.</span><span class="sxs-lookup"><span data-stu-id="a1b40-159">Returns information about activity on Azure SQL databases inside of an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabasesAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabasesAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListDatabasesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b40-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a1b40-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b40-161">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="a1b40-161">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b40-162">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a1b40-162">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b40-163">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="a1b40-163">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a1b40-164">Der Name des SQL Azure elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a1b40-164">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b40-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a1b40-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b40-166">Gibt Informationen zu einer Azure SQL-Datenbank in einem elastischen Pool für SQL Azure.</span><span class="sxs-lookup"><span data-stu-id="a1b40-166">Returns information about an Azure SQL database inside of an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>