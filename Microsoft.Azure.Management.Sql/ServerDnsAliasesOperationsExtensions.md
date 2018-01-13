<Type Name="ServerDnsAliasesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServerDnsAliasesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServerDnsAliasesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServerDnsAliasesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServerDnsAliasesOperationsExtensions = class" />
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
            <span data-ttu-id="f7c33-101">Erweiterungsmethoden für ServerDnsAliasesOperations.</span><span class="sxs-lookup"><span data-stu-id="f7c33-101">Extension methods for ServerDnsAliasesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Acquire">
      <MemberSignature Language="C#" Value="public static void Acquire (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Acquire(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Acquire(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Acquire (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String, parameters As ServerDnsAliasAcquisition)" />
      <MemberSignature Language="F#" Value="static member Acquire : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Acquire (operations, resourceGroupName, serverName, dnsAliasName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-105">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-105">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-106">Der Name des Server-Dns-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-106">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <summary>
            <span data-ttu-id="f7c33-107">Ruft den Server-DNS-Alias von einem anderen Server.</span><span class="sxs-lookup"><span data-stu-id="f7c33-107">Acquires server DNS alias from another server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AcquireAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AcquireAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.AcquireAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AcquireAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.AcquireAsync (operations, resourceGroupName, serverName, dnsAliasName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;AcquireAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-109">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-110">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-111">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-111">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-112">Der Name des Server-Dns-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-112">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-114">Ruft den Server-DNS-Alias von einem anderen Server.</span><span class="sxs-lookup"><span data-stu-id="f7c33-114">Acquires server DNS alias from another server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquire">
      <MemberSignature Language="C#" Value="public static void BeginAcquire (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginAcquire(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquire(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginAcquire (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String, parameters As ServerDnsAliasAcquisition)" />
      <MemberSignature Language="F#" Value="static member BeginAcquire : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquire (operations, resourceGroupName, serverName, dnsAliasName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-116">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-117">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-118">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-118">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-119">Der Name des Server-Dns-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-119">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <summary>
            <span data-ttu-id="f7c33-120">Ruft den Server-DNS-Alias von einem anderen Server.</span><span class="sxs-lookup"><span data-stu-id="f7c33-120">Acquires server DNS alias from another server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquireAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginAcquireAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginAcquireAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquireAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginAcquireAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquireAsync (operations, resourceGroupName, serverName, dnsAliasName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;BeginAcquireAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-122">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-123">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-124">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-124">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-125">Der Name des Server-Dns-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-125">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-127">Ruft den Server-DNS-Alias von einem anderen Server.</span><span class="sxs-lookup"><span data-stu-id="f7c33-127">Acquires server DNS alias from another server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerDnsAlias BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String) As ServerDnsAlias" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerDnsAlias" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerDnsAlias</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-129">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-129">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-130">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-130">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-131">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-131">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-132">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-132">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-133">Erstellt einen Server DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-133">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-135">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-136">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-137">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-137">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-138">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-138">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-140">Erstellt einen Server DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-140">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-142">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-142">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-143">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-143">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-144">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-144">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-145">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-145">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-146">Löscht den DNS-Server alias mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="f7c33-146">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-148">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-148">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-149">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-149">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-150">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-150">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-151">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-151">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-153">Löscht den DNS-Server alias mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="f7c33-153">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerDnsAlias CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String) As ServerDnsAlias" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerDnsAlias" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerDnsAlias</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-155">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-155">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-156">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-156">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-157">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-157">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-158">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-158">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-159">Erstellt einen Server DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-159">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-161">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-161">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-162">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-162">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-163">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-163">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-164">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-164">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-166">Erstellt einen Server DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-166">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Delete (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-168">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-168">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-169">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-169">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-170">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-170">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-171">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-171">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-172">Löscht den DNS-Server alias mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="f7c33-172">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-174">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-175">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-176">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-176">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-177">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-177">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-178">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-179">Löscht den DNS-Server alias mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="f7c33-179">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerDnsAlias Get (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias Get(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String) As ServerDnsAlias" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerDnsAlias" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Get (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerDnsAlias</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-181">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-181">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-182">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-182">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-183">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-183">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-184">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-184">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-185">Ruft einen Server ab, das DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-185">Gets a server DNS alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-187">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-187">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-188">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-188">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-189">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-189">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="f7c33-190">Der Name des Server-DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-190">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-192">Ruft einen Server ab, das DNS-Alias.</span><span class="sxs-lookup"><span data-stu-id="f7c33-192">Gets a server DNS alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServer (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServer(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String) As IPage(Of ServerDnsAlias)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-194">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-194">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-195">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-195">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-196">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-196">The name of the server that the alias is pointing to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-197">Ruft eine Liste der Server DNS-Aliase für einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="f7c33-197">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;ListByServerAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7c33-199">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f7c33-199">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7c33-200">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f7c33-200">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7c33-201">Der Name des Servers, der der Alias verweist.</span><span class="sxs-lookup"><span data-stu-id="f7c33-201">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-202">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-203">Ruft eine Liste der Server DNS-Aliase für einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="f7c33-203">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IServerDnsAliasesOperations, nextPageLink As String) As IPage(Of ServerDnsAlias)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-204">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f7c33-205">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f7c33-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-206">Ruft eine Liste der Server DNS-Aliase für einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="f7c33-206">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;ListByServerNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7c33-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f7c33-207">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f7c33-208">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f7c33-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7c33-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7c33-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7c33-210">Ruft eine Liste der Server DNS-Aliase für einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="f7c33-210">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>