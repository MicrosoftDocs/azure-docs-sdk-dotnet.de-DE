<Type Name="RecommendedElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendedElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPoolsOperationsExtensions = class" />
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
            <span data-ttu-id="0d6e1-101">Erweiterungsmethoden für RecommendedElasticPoolsOperations.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-101">Extension methods for RecommendedElasticPoolsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d6e1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d6e1-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0d6e1-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0d6e1-105">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-105">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0d6e1-106">Der Name des Azure SQL empfohlene elastische Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-106">The name of the Azure SQL Recommended Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d6e1-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d6e1-108">Ruft Informationen zu einem Azure SQL empfohlen elastischen Pool ab.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-108">Gets information about an Azure SQL Recommended Elastic Pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabasesAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabasesAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetDatabasesAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatabasesAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetDatabasesAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;GetDatabasesAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d6e1-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d6e1-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0d6e1-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0d6e1-112">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-112">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0d6e1-113">Der Name des SQL Azure elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-113">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="0d6e1-114">Der Name der Azure SQL-Datenbank abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-114">The name of the Azure SQL database to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d6e1-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d6e1-116">Ruft Informationen zu einer Azure SQL-Datenbank in einem Azure SQL empfohlen elastischen Pool ab.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-116">Gets information about an Azure SQL database inside of an Azure SQL Recommended Elastic Pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;ListAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d6e1-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d6e1-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0d6e1-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0d6e1-120">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-120">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d6e1-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d6e1-122">Gibt Informationen zu Azure SQL empfohlene elastische Pools.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-122">Returns information about Azure SQL Recommended Elastic Pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListDatabasesAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListDatabasesAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;ListDatabasesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d6e1-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d6e1-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0d6e1-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0d6e1-126">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-126">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0d6e1-127">Der Name des Azure SQL empfohlene elastische Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-127">The name of the Azure SQL Recommended Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d6e1-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d6e1-129">Gibt Informationen zu einer Azure SQL-Datenbank in einem Azure SQL empfohlen elastischen Pool zurück.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-129">Returns information about an Azure SQL database inside of an Azure SQL Recommended Elastic Pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;ListMetricsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d6e1-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d6e1-131">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="0d6e1-132">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="0d6e1-133">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-133">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="0d6e1-134">Der Name des Azure SQL empfohlene elastische Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-134">The name of the Azure SQL Recommended Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d6e1-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d6e1-136">Gibt Informationen zu einer Metriken empfohlenen elastischen Pool zurück.</span><span class="sxs-lookup"><span data-stu-id="0d6e1-136">Returns information about an recommended elastic pool metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>