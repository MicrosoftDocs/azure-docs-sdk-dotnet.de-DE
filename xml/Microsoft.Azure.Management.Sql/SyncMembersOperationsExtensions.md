<Type Name="SyncMembersOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SyncMembersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SyncMembersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SyncMembersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SyncMembersOperationsExtensions = class" />
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
            <span data-ttu-id="01e7c-101">Erweiterungsmethoden für SyncMembersOperations.</span><span class="sxs-lookup"><span data-stu-id="01e7c-101">Extension methods for SyncMembersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-106">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-106">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-107">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-107">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-108">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-108">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-109">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-109">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-110">Erstellt oder aktualisiert ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-110">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-112">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-113">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-114">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-114">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-115">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-115">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-116">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-116">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-117">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-117">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-118">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-118">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-120">Erstellt oder aktualisiert ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-120">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-122">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-123">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-124">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-124">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-125">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-125">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-126">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-126">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-127">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-127">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-128">Löscht ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-128">Deletes a sync member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-130">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-130">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-131">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-131">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-132">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-132">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-133">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-133">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-134">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-134">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-135">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-135">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-137">Löscht ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-137">Deletes a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshMemberSchema">
      <MemberSignature Language="C#" Value="public static void BeginRefreshMemberSchema (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginRefreshMemberSchema(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchema(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginRefreshMemberSchema (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshMemberSchema : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-139">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-139">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-140">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-141">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-141">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-142">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-142">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-143">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-143">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-144">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-144">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-145">Aktualisiert ein Datenbankschema der Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-145">Refreshes a sync member database schema.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshMemberSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginRefreshMemberSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginRefreshMemberSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchemaAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshMemberSchemaAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginRefreshMemberSchemaAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-147">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-147">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-148">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-148">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-149">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-149">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-150">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-150">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-151">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-151">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-152">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-152">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-154">Aktualisiert ein Datenbankschema der Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-154">Refreshes a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember BeginUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember BeginUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-156">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-156">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-157">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-157">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-158">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-158">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-159">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-159">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-160">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-160">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-161">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-161">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-162">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-162">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-163">Aktualisiert ein vorhandenes Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-163">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-165">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-166">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-167">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-167">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-168">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-168">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-169">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-169">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-170">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-170">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-171">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-171">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-173">Aktualisiert ein vorhandenes Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-173">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember CreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember CreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-175">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-175">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-176">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-176">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-177">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-177">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-178">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-178">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-179">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-179">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-180">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-180">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-181">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-181">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-182">Erstellt oder aktualisiert ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-182">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-184">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-184">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-185">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-185">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-186">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-186">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-187">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-187">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-188">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-188">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-189">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-189">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-190">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-190">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-192">Erstellt oder aktualisiert ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-192">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-194">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-194">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-195">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-195">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-196">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-196">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-197">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-197">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-198">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-198">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-199">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-199">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-200">Löscht ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-200">Deletes a sync member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-202">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-202">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-203">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-203">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-204">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-204">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-205">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-205">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-206">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-206">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-207">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-207">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-209">Löscht ein Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-209">Deletes a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember Get (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember Get(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String) As SyncMember" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-211">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-211">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-212">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-212">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-213">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-213">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-214">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-214">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-215">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-215">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-216">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-216">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-217">Ruft ein Element für die Synchronisierung ab.</span><span class="sxs-lookup"><span data-stu-id="01e7c-217">Gets a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; GetAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; GetAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-219">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-219">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-220">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-220">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-221">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-221">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-222">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-222">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-223">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-223">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-224">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-224">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-226">Ruft ein Element für die Synchronisierung ab.</span><span class="sxs-lookup"><span data-stu-id="01e7c-226">Gets a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroup (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroup(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroup(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySyncGroup (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String) As IPage(Of SyncMember)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroup : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroup (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-228">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-228">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-229">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-229">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-230">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-230">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-231">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-231">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-232">Der Name der Synchronisierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="01e7c-232">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-233">Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="01e7c-233">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListBySyncGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-235">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-235">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-236">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-236">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-237">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-237">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-238">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-238">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-239">Der Name der Synchronisierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="01e7c-239">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-240">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-241">Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="01e7c-241">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroupNext (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroupNext(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNext(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySyncGroupNext (operations As ISyncMembersOperations, nextPageLink As String) As IPage(Of SyncMember)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupNext : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-242">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-242">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01e7c-243">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="01e7c-243">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-244">Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="01e7c-244">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupNextAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupNextAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNextAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupNextAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListBySyncGroupNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-245">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-245">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01e7c-246">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="01e7c-246">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-247">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-248">Listen Elemente in der angegebenen Synchronisierungsgruppe zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="01e7c-248">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemas">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemas (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemas(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemas(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMemberSchemas (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemas : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemas (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-249">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-250">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-250">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-251">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-251">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-252">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-252">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-253">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-253">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-254">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-254">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-255">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-255">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-256">Ruft ein Element Sync Datenbankschema ab.</span><span class="sxs-lookup"><span data-stu-id="01e7c-256">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListMemberSchemasAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-257">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-257">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-258">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-258">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-259">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-259">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-260">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-260">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-261">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-261">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-262">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-262">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-263">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-263">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-264">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-265">Ruft ein Element Sync Datenbankschema ab.</span><span class="sxs-lookup"><span data-stu-id="01e7c-265">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemasNext (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemasNext(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNext(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMemberSchemasNext (operations As ISyncMembersOperations, nextPageLink As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasNext : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-266">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-266">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01e7c-267">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="01e7c-267">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-268">Ruft ein Element Sync Datenbankschema ab.</span><span class="sxs-lookup"><span data-stu-id="01e7c-268">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasNextAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasNextAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNextAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasNextAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListMemberSchemasNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-269">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-269">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01e7c-270">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="01e7c-270">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-271">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-272">Ruft ein Element Sync Datenbankschema ab.</span><span class="sxs-lookup"><span data-stu-id="01e7c-272">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshMemberSchema">
      <MemberSignature Language="C#" Value="public static void RefreshMemberSchema (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RefreshMemberSchema(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchema(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RefreshMemberSchema (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member RefreshMemberSchema : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-273">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-274">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-274">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-275">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-275">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-276">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-276">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-277">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-277">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-278">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-278">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-279">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-279">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-280">Aktualisiert ein Datenbankschema der Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-280">Refreshes a sync member database schema.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshMemberSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RefreshMemberSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RefreshMemberSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchemaAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshMemberSchemaAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;RefreshMemberSchemaAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-281">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-281">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-282">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-282">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-283">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-283">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-284">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-284">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-285">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-285">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-286">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-286">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-287">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-287">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-288">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-289">Aktualisiert ein Datenbankschema der Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-289">Refreshes a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember Update (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember Update(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Update(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Update (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-290">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-290">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-291">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-291">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-292">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-292">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-293">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-293">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-294">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-294">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-295">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-295">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-296">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-296">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-297">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-297">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-298">Aktualisiert ein vorhandenes Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-298">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01e7c-299">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="01e7c-299">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01e7c-300">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="01e7c-300">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="01e7c-301">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="01e7c-301">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="01e7c-302">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="01e7c-302">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="01e7c-303">Der Name der Datenbank auf der die Synchronisierungsgruppe gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-303">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="01e7c-304">Der Name der Synchronisierungsgruppe auf der das Sync-Element gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="01e7c-304">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="01e7c-305">Der Name des Sync-Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-305">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01e7c-306">Der angeforderte Sync Ressourcenstatus des Elements.</span><span class="sxs-lookup"><span data-stu-id="01e7c-306">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01e7c-307">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="01e7c-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01e7c-308">Aktualisiert ein vorhandenes Sync-Element.</span><span class="sxs-lookup"><span data-stu-id="01e7c-308">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>