<Type Name="RecoveryPointsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecoveryPointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecoveryPointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecoveryPointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecoveryPointsOperationsExtensions = class" />
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
            <span data-ttu-id="a3c57-101">Erweiterungsmethoden für RecoveryPointsOperations.</span><span class="sxs-lookup"><span data-stu-id="a3c57-101">Extension methods for RecoveryPointsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRecoveryPointsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String) As RecoveryPointResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3c57-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a3c57-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a3c57-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a3c57-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a3c57-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a3c57-105">Name des Fabric zugeordnet gesichert Element ab.</span><span class="sxs-lookup"><span data-stu-id="a3c57-105">Fabric name associated with backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a3c57-106">Containername zugeordneten gesichert Element ab.</span><span class="sxs-lookup"><span data-stu-id="a3c57-106">Container name associated with backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a3c57-107">Gesichert, der Name des Elements, dessen Sicherungsdaten abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a3c57-107">Backed up item name whose backup data needs to be fetched.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="a3c57-108">%Recoverypointid stellt die gesicherten Daten abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a3c57-108">RecoveryPointID represents the backed up data to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3c57-109">Enthält die Informationen der gesicherten Daten mithilfe von %recoverypointid identifiziert.</span><span class="sxs-lookup"><span data-stu-id="a3c57-109">Provides the information of the backed up data identified using RecoveryPointID.</span></span> <span data-ttu-id="a3c57-110">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a3c57-110">This is an asynchronous operation.</span></span> <span data-ttu-id="a3c57-111">Um den Status des Vorgangs zu kennen, rufen Sie die GetProtectedItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a3c57-111">To know the status of the operation, call the GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3c57-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a3c57-112">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a3c57-113">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a3c57-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a3c57-114">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a3c57-115">Name des Fabric zugeordnet gesichert Element ab.</span><span class="sxs-lookup"><span data-stu-id="a3c57-115">Fabric name associated with backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a3c57-116">Containername zugeordneten gesichert Element ab.</span><span class="sxs-lookup"><span data-stu-id="a3c57-116">Container name associated with backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a3c57-117">Gesichert, der Name des Elements, dessen Sicherungsdaten abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a3c57-117">Backed up item name whose backup data needs to be fetched.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="a3c57-118">%Recoverypointid stellt die gesicherten Daten abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a3c57-118">RecoveryPointID represents the backed up data to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3c57-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a3c57-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3c57-120">Enthält die Informationen der gesicherten Daten mithilfe von %recoverypointid identifiziert.</span><span class="sxs-lookup"><span data-stu-id="a3c57-120">Provides the information of the backed up data identified using RecoveryPointID.</span></span> <span data-ttu-id="a3c57-121">Das ist ein asynchroner Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a3c57-121">This is an asynchronous operation.</span></span> <span data-ttu-id="a3c57-122">Um den Status des Vorgangs zu kennen, rufen Sie die GetProtectedItemOperationResult-API.</span><span class="sxs-lookup"><span data-stu-id="a3c57-122">To know the status of the operation, call the GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRecoveryPointsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, Optional odataQuery As ODataQuery(Of BMSRPQueryObject) = null) As IPage(Of RecoveryPointResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.List (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3c57-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a3c57-123">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a3c57-124">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a3c57-124">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a3c57-125">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-125">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a3c57-126">Name des Fabric gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a3c57-126">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a3c57-127">Der Containername gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a3c57-127">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a3c57-128">Gesichert, Element, dessen Sicherungskopien werden abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a3c57-128">Backed up item whose backup copies are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a3c57-129">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="a3c57-129">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3c57-130">Listet die Sicherungskopien für das Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-130">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3c57-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a3c57-131">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="a3c57-132">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="a3c57-132">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a3c57-133">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-133">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="a3c57-134">Name des Fabric gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a3c57-134">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="a3c57-135">Der Containername gesicherten Element zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a3c57-135">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="a3c57-136">Gesichert, Element, dessen Sicherungskopien werden abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a3c57-136">Backed up item whose backup copies are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a3c57-137">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="a3c57-137">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3c57-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a3c57-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3c57-139">Listet die Sicherungskopien für das Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-139">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRecoveryPointsOperations, nextPageLink As String) As IPage(Of RecoveryPointResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3c57-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a3c57-140">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a3c57-141">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a3c57-141">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3c57-142">Listet die Sicherungskopien für das Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-142">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3c57-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a3c57-143">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a3c57-144">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a3c57-144">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3c57-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a3c57-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3c57-146">Listet die Sicherungskopien für das Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="a3c57-146">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>