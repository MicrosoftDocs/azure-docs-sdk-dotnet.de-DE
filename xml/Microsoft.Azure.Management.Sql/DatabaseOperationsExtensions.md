<Type Name="DatabaseOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabaseOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabaseOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabaseOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabaseOperationsExtensions = class" />
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
            <span data-ttu-id="6c404-101">Erweiterungsmethoden für DatabaseOperations.</span><span class="sxs-lookup"><span data-stu-id="6c404-101">Extension methods for DatabaseOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public static void Cancel (this Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName, Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Cancel(class Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.Cancel(Microsoft.Azure.Management.Sql.IDatabaseOperations,System.String,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Cancel (operations As IDatabaseOperations, resourceGroupName As String, serverName As String, databaseName As String, operationId As Guid)" />
      <MemberSignature Language="F#" Value="static member Cancel : Microsoft.Azure.Management.Sql.IDatabaseOperations * string * string * string * Guid -&gt; unit" Usage="Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.Cancel (operations, resourceGroupName, serverName, databaseName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c404-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c404-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c404-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c404-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6c404-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="6c404-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6c404-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="6c404-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6c404-106">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="6c404-106">The name of the database.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="6c404-107">Der Vorgangsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6c404-107">The operation identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c404-108">Bricht den asynchronen Vorgang für die Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="6c404-108">Cancels the asynchronous operation on the database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelAsync (this Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName, Guid operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelAsync(class Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.CancelAsync(Microsoft.Azure.Management.Sql.IDatabaseOperations,System.String,System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelAsync : Microsoft.Azure.Management.Sql.IDatabaseOperations * string * string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.CancelAsync (operations, resourceGroupName, serverName, databaseName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions/&lt;CancelAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c404-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c404-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c404-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c404-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6c404-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="6c404-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6c404-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="6c404-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6c404-113">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="6c404-113">The name of the database.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="6c404-114">Der Vorgangsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6c404-114">The operation identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c404-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c404-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c404-116">Bricht den asynchronen Vorgang für die Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="6c404-116">Cancels the asynchronous operation on the database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IDatabaseOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IDatabaseOperations, resourceGroupName As String, serverName As String, databaseName As String) As IPage(Of DatabaseOperation)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IDatabaseOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c404-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c404-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c404-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c404-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6c404-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="6c404-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6c404-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="6c404-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6c404-121">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="6c404-121">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c404-122">Ruft eine Liste der durchgeführten Operationen für die Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="6c404-122">Gets a list of operations performed on the database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IDatabaseOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IDatabaseOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c404-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c404-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c404-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c404-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6c404-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="6c404-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6c404-126">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="6c404-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6c404-127">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="6c404-127">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c404-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c404-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c404-129">Ruft eine Liste der durchgeführten Operationen für die Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="6c404-129">Gets a list of operations performed on the database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt; ListByDatabaseNext (this Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt; ListByDatabaseNext(class Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabaseNext(Microsoft.Azure.Management.Sql.IDatabaseOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabaseNext (operations As IDatabaseOperations, nextPageLink As String) As IPage(Of DatabaseOperation)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseNext : Microsoft.Azure.Management.Sql.IDatabaseOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c404-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c404-130">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6c404-131">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6c404-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c404-132">Ruft eine Liste der durchgeführten Operationen für die Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="6c404-132">Gets a list of operations performed on the database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt; ListByDatabaseNextAsync (this Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt; ListByDatabaseNextAsync(class Microsoft.Azure.Management.Sql.IDatabaseOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabaseNextAsync(Microsoft.Azure.Management.Sql.IDatabaseOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseNextAsync : Microsoft.Azure.Management.Sql.IDatabaseOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions.ListByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseOperationsExtensions/&lt;ListByDatabaseNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.DatabaseOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c404-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c404-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6c404-134">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6c404-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c404-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c404-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c404-136">Ruft eine Liste der durchgeführten Operationen für die Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="6c404-136">Gets a list of operations performed on the database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>