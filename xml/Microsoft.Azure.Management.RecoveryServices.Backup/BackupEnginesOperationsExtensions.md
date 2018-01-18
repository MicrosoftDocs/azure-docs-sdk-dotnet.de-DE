<Type Name="BackupEnginesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupEnginesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupEnginesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupEnginesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupEnginesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6a185-101">Erweiterungsmethoden für BackupEnginesOperations.</span><span class="sxs-lookup"><span data-stu-id="6a185-101">Extension methods for BackupEnginesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery = null, string skipToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery, string skipToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupEnginesOperations, vaultName As String, resourceGroupName As String, backupEngineName As String, Optional odataQuery As ODataQuery(Of BMSBackupEngineQueryObject) = null, Optional skipToken As String = null) As BackupEngineBaseResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.Get (operations, vaultName, resourceGroupName, backupEngineName, odataQuery, skipToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="backupEngineName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a185-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a185-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="6a185-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="6a185-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a185-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="6a185-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="backupEngineName">
            <span data-ttu-id="6a185-105">Der Name des backup-Verwaltungsservers.</span><span class="sxs-lookup"><span data-stu-id="6a185-105">Name of the backup management server.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6a185-106">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6a185-106">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="6a185-107">SkipToken Filter.</span><span class="sxs-lookup"><span data-stu-id="6a185-107">skipToken Filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a185-108">Gibt backup Verwaltungsserver registriert, Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="6a185-108">Returns backup management server registered to Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery = null, string skipToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery, string skipToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, backupEngineName, odataQuery, skipToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="backupEngineName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a185-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a185-109">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="6a185-110">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="6a185-110">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a185-111">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="6a185-111">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="backupEngineName">
            <span data-ttu-id="6a185-112">Der Name des backup-Verwaltungsservers.</span><span class="sxs-lookup"><span data-stu-id="6a185-112">Name of the backup management server.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6a185-113">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6a185-113">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="6a185-114">SkipToken Filter.</span><span class="sxs-lookup"><span data-stu-id="6a185-114">skipToken Filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a185-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a185-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a185-116">Gibt backup Verwaltungsserver registriert, Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="6a185-116">Returns backup management server registered to Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery = null, string skipToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery, string skipToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBackupEnginesOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of BMSBackupEnginesQueryObject) = null, Optional skipToken As String = null) As IPage(Of BackupEngineBaseResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.List (operations, vaultName, resourceGroupName, odataQuery, skipToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a185-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a185-117">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="6a185-118">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="6a185-118">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a185-119">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="6a185-119">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6a185-120">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6a185-120">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="6a185-121">SkipToken Filter.</span><span class="sxs-lookup"><span data-stu-id="6a185-121">skipToken Filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a185-122">Backup-Management-Server Recovery Services-Tresor registriert.</span><span class="sxs-lookup"><span data-stu-id="6a185-122">Backup management servers registered to Recovery Services Vault.</span></span> <span data-ttu-id="6a185-123">Gibt eine auslagerbaren Liste mit Servern zurück.</span><span class="sxs-lookup"><span data-stu-id="6a185-123">Returns a pageable list of servers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery = null, string skipToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery, string skipToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, odataQuery, skipToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a185-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a185-124">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="6a185-125">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="6a185-125">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6a185-126">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="6a185-126">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6a185-127">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6a185-127">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="6a185-128">SkipToken Filter.</span><span class="sxs-lookup"><span data-stu-id="6a185-128">skipToken Filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a185-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a185-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a185-130">Backup-Management-Server Recovery Services-Tresor registriert.</span><span class="sxs-lookup"><span data-stu-id="6a185-130">Backup management servers registered to Recovery Services Vault.</span></span> <span data-ttu-id="6a185-131">Gibt eine auslagerbaren Liste mit Servern zurück.</span><span class="sxs-lookup"><span data-stu-id="6a185-131">Returns a pageable list of servers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBackupEnginesOperations, nextPageLink As String) As IPage(Of BackupEngineBaseResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a185-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a185-132">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6a185-133">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6a185-133">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a185-134">Backup-Management-Server Recovery Services-Tresor registriert.</span><span class="sxs-lookup"><span data-stu-id="6a185-134">Backup management servers registered to Recovery Services Vault.</span></span> <span data-ttu-id="6a185-135">Gibt eine auslagerbaren Liste mit Servern zurück.</span><span class="sxs-lookup"><span data-stu-id="6a185-135">Returns a pageable list of servers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6a185-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6a185-136">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6a185-137">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6a185-137">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6a185-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6a185-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6a185-139">Backup-Management-Server Recovery Services-Tresor registriert.</span><span class="sxs-lookup"><span data-stu-id="6a185-139">Backup management servers registered to Recovery Services Vault.</span></span> <span data-ttu-id="6a185-140">Gibt eine auslagerbaren Liste mit Servern zurück.</span><span class="sxs-lookup"><span data-stu-id="6a185-140">Returns a pageable list of servers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>