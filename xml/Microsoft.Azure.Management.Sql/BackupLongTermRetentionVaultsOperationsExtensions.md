<Type Name="BackupLongTermRetentionVaultsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupLongTermRetentionVaultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupLongTermRetentionVaultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupLongTermRetentionVaultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupLongTermRetentionVaultsOperationsExtensions = class" />
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
            <span data-ttu-id="5ce03-101">Erweiterungsmethoden für BackupLongTermRetentionVaultsOperations.</span><span class="sxs-lookup"><span data-stu-id="5ce03-101">Extension methods for BackupLongTermRetentionVaultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IBackupLongTermRetentionVaultsOperations, resourceGroupName As String, serverName As String, parameters As BackupLongTermRetentionVault) As BackupLongTermRetentionVault" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ce03-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5ce03-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ce03-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="5ce03-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5ce03-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5ce03-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5ce03-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="5ce03-105">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ce03-106">Die erforderlichen Parameter einen backup langfristige Aufbewahrung Tresor aktualisieren</span><span class="sxs-lookup"><span data-stu-id="5ce03-106">The required parameters to update a backup long term retention vault</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ce03-107">Aktualisiert einen Server backup langfristige Aufbewahrung Tresor</span><span class="sxs-lookup"><span data-stu-id="5ce03-107">Updates a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ce03-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5ce03-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ce03-109">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="5ce03-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5ce03-110">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5ce03-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5ce03-111">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="5ce03-111">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ce03-112">Die erforderlichen Parameter einen backup langfristige Aufbewahrung Tresor aktualisieren</span><span class="sxs-lookup"><span data-stu-id="5ce03-112">The required parameters to update a backup long term retention vault</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ce03-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5ce03-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ce03-114">Aktualisiert einen Server backup langfristige Aufbewahrung Tresor</span><span class="sxs-lookup"><span data-stu-id="5ce03-114">Updates a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault CreateOrUpdate (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault CreateOrUpdate(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IBackupLongTermRetentionVaultsOperations, resourceGroupName As String, serverName As String, parameters As BackupLongTermRetentionVault) As BackupLongTermRetentionVault" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ce03-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5ce03-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ce03-116">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="5ce03-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5ce03-117">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5ce03-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5ce03-118">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="5ce03-118">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ce03-119">Die erforderlichen Parameter einen backup langfristige Aufbewahrung Tresor aktualisieren</span><span class="sxs-lookup"><span data-stu-id="5ce03-119">The required parameters to update a backup long term retention vault</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ce03-120">Aktualisiert einen Server backup langfristige Aufbewahrung Tresor</span><span class="sxs-lookup"><span data-stu-id="5ce03-120">Updates a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ce03-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5ce03-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ce03-122">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="5ce03-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5ce03-123">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5ce03-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5ce03-124">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="5ce03-124">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ce03-125">Die erforderlichen Parameter einen backup langfristige Aufbewahrung Tresor aktualisieren</span><span class="sxs-lookup"><span data-stu-id="5ce03-125">The required parameters to update a backup long term retention vault</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ce03-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5ce03-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ce03-127">Aktualisiert einen Server backup langfristige Aufbewahrung Tresor</span><span class="sxs-lookup"><span data-stu-id="5ce03-127">Updates a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault Get (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault Get(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupLongTermRetentionVaultsOperations, resourceGroupName As String, serverName As String) As BackupLongTermRetentionVault" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.Get (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ce03-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5ce03-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ce03-129">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="5ce03-129">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5ce03-130">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5ce03-130">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5ce03-131">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="5ce03-131">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ce03-132">Ruft einen Server backup langfristige Aufbewahrung Tresor</span><span class="sxs-lookup"><span data-stu-id="5ce03-132">Gets a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt; GetAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt; GetAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionVaultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ce03-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5ce03-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ce03-134">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="5ce03-134">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5ce03-135">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5ce03-135">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5ce03-136">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="5ce03-136">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ce03-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5ce03-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ce03-138">Ruft einen Server backup langfristige Aufbewahrung Tresor</span><span class="sxs-lookup"><span data-stu-id="5ce03-138">Gets a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>