<Type Name="SnapshotsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SnapshotsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SnapshotsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SnapshotsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SnapshotsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4c31e-101">Erweiterungsmethoden für SnapshotsOperations.</span><span class="sxs-lookup"><span data-stu-id="4c31e-101">Extension methods for SnapshotsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-103">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-104">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-104">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-105">Momentaufnahmeobjekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-105">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-106">Erstellt oder aktualisiert eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-106">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-108">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-109">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-109">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-110">Momentaufnahmeobjekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-110">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-112">Erstellt oder aktualisiert eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-112">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDelete (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-114">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-115">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-115">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-116">Löscht eine Momentaufnahme an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-116">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-118">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-119">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-119">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-121">Löscht eine Momentaufnahme an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-121">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AccessUri BeginGrantAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AccessUri BeginGrantAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData -&gt; Microsoft.Azure.Management.Compute.Models.AccessUri" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccess (operations, resourceGroupName, snapshotName, grantAccessData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AccessUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-123">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-124">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-124">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="4c31e-125">Zugriff Datenobjekt, das im Text des Get-Vorgangs für die Momentaufnahme Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-125">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-126">Gewährt Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-126">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt; BeginGrantAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AccessUri&gt; BeginGrantAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginGrantAccessAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-128">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-129">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-129">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="4c31e-130">Zugriff Datenobjekt, das im Text des Get-Vorgangs für die Momentaufnahme Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-130">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-132">Gewährt Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-132">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRevokeAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRevokeAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRevokeAccess (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccess (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-134">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-135">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-135">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-136">Hebt den Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-136">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRevokeAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRevokeAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginRevokeAccessAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-138">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-138">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-139">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-139">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-141">Hebt den Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-141">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot BeginUpdate (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot BeginUpdate(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdate (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-143">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-143">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-144">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-144">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-145">Momentaufnahme-Objekt im Text des Momentaufnahme-Patch-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-145">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-146">Updates (Patches) eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-146">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-148">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-148">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-149">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-149">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-150">Momentaufnahme-Objekt im Text des Momentaufnahme-Patch-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-150">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-152">Updates (Patches) eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-152">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot CreateOrUpdate (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot CreateOrUpdate(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-154">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-155">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-155">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-156">Momentaufnahmeobjekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-156">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-157">Erstellt oder aktualisiert eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-157">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-159">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-160">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-160">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-161">Momentaufnahmeobjekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-161">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-163">Erstellt oder aktualisiert eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-163">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Delete (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-165">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-165">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-166">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-166">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-167">Löscht eine Momentaufnahme an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-167">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.DeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-169">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-169">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-170">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-170">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-172">Löscht eine Momentaufnahme an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-172">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot Get (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot Get(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As Snapshot" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Get (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-174">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-174">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-175">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-175">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-176">Ruft Informationen zu einer Momentaufnahme ab.</span><span class="sxs-lookup"><span data-stu-id="4c31e-176">Gets information about a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; GetAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; GetAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GetAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-178">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-178">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-179">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-179">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-181">Ruft Informationen zu einer Momentaufnahme ab.</span><span class="sxs-lookup"><span data-stu-id="4c31e-181">Gets information about a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AccessUri GrantAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AccessUri GrantAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData)" />
      <MemberSignature Language="F#" Value="static member GrantAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData -&gt; Microsoft.Azure.Management.Compute.Models.AccessUri" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccess (operations, resourceGroupName, snapshotName, grantAccessData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AccessUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-183">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-183">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-184">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-184">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="4c31e-185">Zugriff Datenobjekt, das im Text des Get-Vorgangs für die Momentaufnahme Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-185">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-186">Gewährt Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-186">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt; GrantAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AccessUri&gt; GrantAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GrantAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;GrantAccessAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-188">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-188">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-189">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-189">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="4c31e-190">Zugriff Datenobjekt, das im Text des Get-Vorgangs für die Momentaufnahme Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-190">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-192">Gewährt Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-192">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; List (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; List(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.List(Microsoft.Azure.Management.Compute.ISnapshotsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISnapshotsOperations) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.ISnapshotsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-193">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-194">Listet Momentaufnahmen unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-194">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-195">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-197">Listet Momentaufnahmen unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-197">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroup (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroup(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As ISnapshotsOperations, resourceGroupName As String) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-199">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-199">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-200">Listet Momentaufnahmen unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-200">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-202">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-202">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-204">Listet Momentaufnahmen unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-204">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As ISnapshotsOperations, nextPageLink As String) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4c31e-206">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c31e-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-207">Listet Momentaufnahmen unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-207">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-208">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4c31e-209">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c31e-209">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-211">Listet Momentaufnahmen unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-211">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListNext (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListNext(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISnapshotsOperations, nextPageLink As String) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-212">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4c31e-213">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c31e-213">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-214">Listet Momentaufnahmen unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-214">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4c31e-216">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c31e-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-217">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-218">Listet Momentaufnahmen unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="4c31e-218">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse RevokeAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse RevokeAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RevokeAccess (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member RevokeAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccess (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-219">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-220">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-220">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-221">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-221">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-222">Hebt den Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-222">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RevokeAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RevokeAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;RevokeAccessAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-224">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-224">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-225">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-225">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-226">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-227">Hebt den Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-227">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot Update (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot Update(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Update(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Update (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-229">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-229">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-230">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-230">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-231">Momentaufnahme-Objekt im Text des Momentaufnahme-Patch-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-231">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-232">Updates (Patches) eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-232">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.UpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4c31e-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-234">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4c31e-234">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4c31e-235">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="4c31e-235">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4c31e-236">Momentaufnahme-Objekt im Text des Momentaufnahme-Patch-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="4c31e-236">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-237">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4c31e-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-238">Updates (Patches) eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="4c31e-238">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>