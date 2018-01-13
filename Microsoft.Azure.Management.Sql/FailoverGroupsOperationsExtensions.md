<Type Name="FailoverGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FailoverGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FailoverGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FailoverGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FailoverGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="229db-101">Erweiterungsmethoden für FailoverGroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="229db-101">Extension methods for FailoverGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroup) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-105">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-105">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-106">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-106">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-107">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-107">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-108">Erstellt oder aktualisiert eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-108">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-112">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-112">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-113">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-113">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-114">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-114">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-116">Erstellt oder aktualisiert eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-116">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-120">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-120">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-121">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-121">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-122">Löscht eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-122">Deletes a failover group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-126">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-126">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-127">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-127">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-129">Löscht eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-129">Deletes a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailover">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginFailover (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginFailover(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailover(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginFailover (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginFailover : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailover (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-131">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-132">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-133">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-133">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-134">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-134">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-135">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-135">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginFailoverAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginFailoverAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailoverAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailoverAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginFailoverAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-137">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-138">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-139">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-139">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-140">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-140">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-142">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-142">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginForceFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginForceFailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginForceFailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginForceFailoverAllowDataLoss (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginForceFailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLoss (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-144">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-145">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-146">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-146">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-147">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-147">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-148">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-148">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="229db-149">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="229db-149">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginForceFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginForceFailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginForceFailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginForceFailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLossAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginForceFailoverAllowDataLossAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-151">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-151">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-152">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-152">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-153">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-153">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-154">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-154">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-156">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-156">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="229db-157">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="229db-157">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginUpdate (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginUpdate(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroupUpdate) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-159">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-160">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-161">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-161">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-162">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-162">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-163">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-163">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-164">Aktualisiert eine Failovergruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-164">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-166">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-166">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-167">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-167">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-168">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-168">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-169">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-169">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-170">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-170">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-172">Aktualisiert eine Failovergruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-172">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup CreateOrUpdate (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup CreateOrUpdate(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroup) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-174">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-175">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-176">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-176">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-177">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-177">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-178">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-178">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-179">Erstellt oder aktualisiert eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-179">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-181">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-181">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-182">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-182">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-183">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-183">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-184">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-184">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-185">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-185">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-187">Erstellt oder aktualisiert eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-187">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Delete (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-189">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-189">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-190">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-190">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-191">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-191">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-192">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-192">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-193">Löscht eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-193">Deletes a failover group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-195">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-195">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-196">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-196">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-197">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-197">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-198">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-198">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-200">Löscht eine Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-200">Deletes a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup Failover (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup Failover(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Failover(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Failover (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member Failover : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Failover (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-202">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-202">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-203">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-203">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-204">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-204">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-205">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-205">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-206">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-206">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; FailoverAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; FailoverAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.FailoverAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.FailoverAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;FailoverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-207">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-208">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-208">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-209">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-209">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-210">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-210">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-211">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-211">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-213">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-213">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup ForceFailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup ForceFailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ForceFailoverAllowDataLoss (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member ForceFailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLoss (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-215">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-215">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-216">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-216">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-217">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-217">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-218">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-218">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-219">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-219">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="229db-220">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="229db-220">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ForceFailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ForceFailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForceFailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLossAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;ForceFailoverAllowDataLossAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-222">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-222">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-223">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-223">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-224">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-224">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-225">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-225">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-226">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-227">Führt ein Failover vom aktuellen primären Server auf diesen Server durch.</span><span class="sxs-lookup"><span data-stu-id="229db-227">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="229db-228">Bei diesem Vorgang können Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="229db-228">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup Get (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup Get(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Get (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-230">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-230">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-231">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-231">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-232">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-232">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-233">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-233">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-234">Ruft eine Failovergruppe ab.</span><span class="sxs-lookup"><span data-stu-id="229db-234">Gets a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; GetAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; GetAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-235">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-236">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-236">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-237">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-237">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-238">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-238">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-239">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-239">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-240">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-241">Ruft eine Failovergruppe ab.</span><span class="sxs-lookup"><span data-stu-id="229db-241">Gets a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServer (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServer(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String) As IPage(Of FailoverGroup)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-242">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-243">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-243">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-244">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-244">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-245">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-245">The name of the server containing the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-246">Listet die Failovergruppen eines Servers auf.</span><span class="sxs-lookup"><span data-stu-id="229db-246">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;ListByServerAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-248">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-248">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-249">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-249">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-250">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-250">The name of the server containing the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-251">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-252">Listet die Failovergruppen eines Servers auf.</span><span class="sxs-lookup"><span data-stu-id="229db-252">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IFailoverGroupsOperations, nextPageLink As String) As IPage(Of FailoverGroup)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-253">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-253">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="229db-254">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="229db-254">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-255">Listet die Failovergruppen eines Servers auf.</span><span class="sxs-lookup"><span data-stu-id="229db-255">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;ListByServerNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-256">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="229db-257">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="229db-257">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-258">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-259">Listet die Failovergruppen eines Servers auf.</span><span class="sxs-lookup"><span data-stu-id="229db-259">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup Update (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup Update(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Update(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroupUpdate) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Update (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-260">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-261">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-261">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-262">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-262">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-263">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-263">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-264">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-264">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-265">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-265">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-266">Aktualisiert eine Failovergruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-266">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="229db-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="229db-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="229db-268">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="229db-268">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="229db-269">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="229db-269">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="229db-270">Der Name des Servers mit der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-270">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="229db-271">Der Name der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="229db-271">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="229db-272">Die Parameter für den Failover-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-272">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="229db-273">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="229db-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="229db-274">Aktualisiert eine Failovergruppe.</span><span class="sxs-lookup"><span data-stu-id="229db-274">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>