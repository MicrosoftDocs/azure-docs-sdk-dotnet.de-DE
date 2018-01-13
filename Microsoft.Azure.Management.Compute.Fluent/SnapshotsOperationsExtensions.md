<Type Name="SnapshotsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SnapshotsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SnapshotsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SnapshotsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SnapshotsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="57dcc-101">Erweiterungsmethoden für SnapshotsOperations.</span><span class="sxs-lookup"><span data-stu-id="57dcc-101">Extension methods for SnapshotsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-103">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-104">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-104">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="57dcc-105">Momentaufnahmeobjekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="57dcc-105">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-107">Erstellt oder aktualisiert eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-107">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-109">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-110">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-110">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-112">Löscht eine Momentaufnahme an.</span><span class="sxs-lookup"><span data-stu-id="57dcc-112">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginGrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginGrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginGrantAccessAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-114">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-115">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-115">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="57dcc-116">Zugriff Datenobjekt, das im Text des Get-Vorgangs für die Momentaufnahme Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="57dcc-116">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-118">Gewährt Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-118">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginRevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginRevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginRevokeAccessAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-120">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-121">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-121">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-123">Hebt den Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-123">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-125">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-126">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-126">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="57dcc-127">Momentaufnahme-Objekt im Text des Momentaufnahme-Patch-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="57dcc-127">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-129">Updates (Patches) eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-129">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-131">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-132">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-132">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="57dcc-133">Momentaufnahmeobjekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="57dcc-133">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-135">Erstellt oder aktualisiert eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-135">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.DeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-137">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-137">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-138">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-138">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-140">Löscht eine Momentaufnahme an.</span><span class="sxs-lookup"><span data-stu-id="57dcc-140">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GetAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-142">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-143">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-143">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-145">Ruft Informationen zu einer Momentaufnahme ab.</span><span class="sxs-lookup"><span data-stu-id="57dcc-145">Gets information about a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;GrantAccessAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-147">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-148">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-148">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="57dcc-149">Zugriff Datenobjekt, das im Text des Get-Vorgangs für die Momentaufnahme Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="57dcc-149">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-151">Gewährt Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-151">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-152">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-154">Listet Momentaufnahmen unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="57dcc-154">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-156">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-158">Listet Momentaufnahmen unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-158">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-159">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="57dcc-160">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="57dcc-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-162">Listet Momentaufnahmen unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-162">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-163">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="57dcc-164">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="57dcc-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-166">Listet Momentaufnahmen unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="57dcc-166">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.RevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.RevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;RevokeAccessAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-168">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-169">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-169">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-171">Hebt den Zugriff auf eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-171">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.UpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57dcc-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57dcc-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57dcc-173">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="57dcc-173">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="57dcc-174">Der Name der Momentaufnahme in die angegebene Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="57dcc-174">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="57dcc-175">Momentaufnahme-Objekt im Text des Momentaufnahme-Patch-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="57dcc-175">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57dcc-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57dcc-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57dcc-177">Updates (Patches) eine Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="57dcc-177">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>