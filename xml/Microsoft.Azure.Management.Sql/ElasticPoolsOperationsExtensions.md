<Type Name="ElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolsOperationsExtensions = class" />
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
            <span data-ttu-id="13305-101">Erweiterungsmethoden für ElasticPoolsOperations.</span><span class="sxs-lookup"><span data-stu-id="13305-101">Extension methods for ElasticPoolsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPool) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-105">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-106">Der Name des elastischen Pools verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="13305-106">The name of the elastic pool to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-107">Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="13305-107">The required parameters for creating or updating an elastic pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-108">Erstellt einen neuen Pool für elastische Datenbanken oder aktualisiert einen vorhandenen elastischen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-108">Creates a new elastic pool or updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-112">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-113">Der Name des elastischen Pools verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="13305-113">The name of the elastic pool to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-114">Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="13305-114">The required parameters for creating or updating an elastic pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-116">Erstellt einen neuen Pool für elastische Datenbanken oder aktualisiert einen vorhandenen elastischen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-116">Creates a new elastic pool or updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool BeginUpdate (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool BeginUpdate(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPoolUpdate) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-120">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-121">Der Name des elastischen Pools aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="13305-121">The name of the elastic pool to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-122">Die erforderlichen Parameter für einen elastischen Pool aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="13305-122">The required parameters for updating an elastic pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-123">Aktualisiert einen vorhandenen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-123">Updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-125">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-125">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-126">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-126">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-127">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-127">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-128">Der Name des elastischen Pools aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="13305-128">The name of the elastic pool to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-129">Die erforderlichen Parameter für einen elastischen Pool aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="13305-129">The required parameters for updating an elastic pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-131">Aktualisiert einen vorhandenen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-131">Updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool CreateOrUpdate (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool CreateOrUpdate(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPool) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-133">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-134">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-135">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-135">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-136">Der Name des elastischen Pools verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="13305-136">The name of the elastic pool to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-137">Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="13305-137">The required parameters for creating or updating an elastic pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-138">Erstellt einen neuen Pool für elastische Datenbanken oder aktualisiert einen vorhandenen elastischen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-138">Creates a new elastic pool or updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-140">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-140">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-141">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-141">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-142">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-142">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-143">Der Name des elastischen Pools verarbeitet werden sollen (aktualisiert oder erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="13305-143">The name of the elastic pool to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-144">Die erforderlichen Parameter zum Erstellen oder Aktualisieren von einem elastischen Pool.</span><span class="sxs-lookup"><span data-stu-id="13305-144">The required parameters for creating or updating an elastic pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-146">Erstellt einen neuen Pool für elastische Datenbanken oder aktualisiert einen vorhandenen elastischen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-146">Creates a new elastic pool or updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Delete (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-148">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-148">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-149">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-149">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-150">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-150">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-151">Der Name des elastischen Pools gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="13305-151">The name of the elastic pool to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-152">Löscht den Pool für elastische Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="13305-152">Deletes the elastic pool.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-154">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-154">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-155">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-155">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-156">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-156">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-157">Der Name des elastischen Pools gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="13305-157">The name of the elastic pool to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-159">Löscht den Pool für elastische Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="13305-159">Deletes the elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool Get (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool Get(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Get (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-161">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-161">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-162">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-162">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-163">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-163">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-164">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="13305-164">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-165">Ruft einen Pool für elastische Datenbanken ab</span><span class="sxs-lookup"><span data-stu-id="13305-165">Gets an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; GetAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; GetAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-167">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-168">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-169">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-169">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-170">Der Name des elastischen Pools abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="13305-170">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-172">Ruft einen Pool für elastische Datenbanken ab</span><span class="sxs-lookup"><span data-stu-id="13305-172">Gets an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; ListByServer (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; ListByServer(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of ElasticPool)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-174">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-175">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-176">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-176">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-177">Gibt eine Liste der Pools für elastische Datenbanken auf einem Server zurück.</span><span class="sxs-lookup"><span data-stu-id="13305-177">Returns a list of elastic pools in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;ListByServerAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-179">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-179">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-180">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-180">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-181">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-181">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-183">Gibt eine Liste der Pools für elastische Datenbanken auf einem Server zurück.</span><span class="sxs-lookup"><span data-stu-id="13305-183">Returns a list of elastic pools in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitions">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt; ListMetricDefinitions (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt; ListMetricDefinitions(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitions(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinitions (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitions : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitions (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-185">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-185">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-186">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-186">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-187">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-187">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-188">Der Name des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="13305-188">The name of the elastic pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-189">Gibt elastischen Pool metrikdefinitionen zurück.</span><span class="sxs-lookup"><span data-stu-id="13305-189">Returns elastic pool metric definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitionsAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionsAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitionsAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;ListMetricDefinitionsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-191">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-191">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-192">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-192">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-193">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-193">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-194">Der Name des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="13305-194">The name of the elastic pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-195">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-196">Gibt elastischen Pool metrikdefinitionen zurück.</span><span class="sxs-lookup"><span data-stu-id="13305-196">Returns elastic pool metric definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt; ListMetrics (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Metric&gt; ListMetrics(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetrics(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, filter As String) As IEnumerable(Of Metric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetrics (operations, resourceGroupName, serverName, elasticPoolName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-198">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-198">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-199">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-199">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-200">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-200">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-201">Der Name des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="13305-201">The name of the elastic pool.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="13305-202">Ein OData-Filterausdruck, der eine Teilmenge der zurückzugebenden Metriken beschreibt.</span><span class="sxs-lookup"><span data-stu-id="13305-202">An OData filter expression that describes a subset of metrics to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-203">Gibt Metriken für elastischen Pool zurück.</span><span class="sxs-lookup"><span data-stu-id="13305-203">Returns elastic pool  metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, serverName, elasticPoolName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;ListMetricsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-205">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-205">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-206">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-206">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-207">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-207">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-208">Der Name des elastischen Pools.</span><span class="sxs-lookup"><span data-stu-id="13305-208">The name of the elastic pool.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="13305-209">Ein OData-Filterausdruck, der eine Teilmenge der zurückzugebenden Metriken beschreibt.</span><span class="sxs-lookup"><span data-stu-id="13305-209">An OData filter expression that describes a subset of metrics to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-211">Gibt Metriken für elastischen Pool zurück.</span><span class="sxs-lookup"><span data-stu-id="13305-211">Returns elastic pool  metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool Update (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool Update(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Update(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPoolUpdate) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Update (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-213">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-213">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-214">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-214">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-215">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-215">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-216">Der Name des elastischen Pools aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="13305-216">The name of the elastic pool to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-217">Die erforderlichen Parameter für einen elastischen Pool aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="13305-217">The required parameters for updating an elastic pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-218">Aktualisiert einen vorhandenen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-218">Updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="13305-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="13305-219">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="13305-220">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="13305-220">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="13305-221">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="13305-221">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="13305-222">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="13305-222">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="13305-223">Der Name des elastischen Pools aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="13305-223">The name of the elastic pool to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="13305-224">Die erforderlichen Parameter für einen elastischen Pool aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="13305-224">The required parameters for updating an elastic pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="13305-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="13305-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="13305-226">Aktualisiert einen vorhandenen Pool für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="13305-226">Updates an existing elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>