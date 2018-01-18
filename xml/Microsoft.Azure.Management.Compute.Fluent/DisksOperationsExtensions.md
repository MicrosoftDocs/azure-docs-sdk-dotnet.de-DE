<Type Name="DisksOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DisksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DisksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DisksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DisksOperationsExtensions = class" />
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
            <span data-ttu-id="9e980-101">Erweiterungsmethoden für DisksOperations.</span><span class="sxs-lookup"><span data-stu-id="9e980-101">Extension methods for DisksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-103">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-104">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-104">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="9e980-105">Disk-Objekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e980-105">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-107">Erstellt oder aktualisiert einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-107">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-109">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-110">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-110">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-112">Löscht einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-112">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginGrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginGrantAccessAsync (operations, resourceGroupName, diskName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginGrantAccessAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-114">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-115">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-115">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="9e980-116">Zugriff Datenobjekt, das im Text des Abrufvorgangs Datenträger Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e980-116">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-118">Gewährt den Zugriff auf einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-118">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginRevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginRevokeAccessAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginRevokeAccessAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-120">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-121">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-121">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-123">Hebt den Zugriff auf einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-123">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-125">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-126">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-126">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="9e980-127">Disk-Objekt im Text des Patch-Vorgangs Datenträger angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e980-127">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-129">Updates (Patches) einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-129">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-131">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-132">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-132">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="9e980-133">Disk-Objekt im Text der Put-Datenträgervorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e980-133">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-135">Erstellt oder aktualisiert einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-135">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.DeleteAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-137">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-137">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-138">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-138">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-140">Löscht einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-140">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GetAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-142">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-143">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-143">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-145">Ruft Informationen über einen Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="9e980-145">Gets information about a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GrantAccessAsync (operations, resourceGroupName, diskName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;GrantAccessAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-147">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-148">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-148">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="9e980-149">Zugriff Datenobjekt, das im Text des Abrufvorgangs Datenträger Zugriff angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e980-149">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-151">Gewährt den Zugriff auf einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-151">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-152">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-154">Listet alle Datenträger unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="9e980-154">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-156">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-158">Listet alle Datenträger, die sich unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-158">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-159">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9e980-160">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9e980-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-162">Listet alle Datenträger, die sich unterhalb einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-162">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-163">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9e980-164">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9e980-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-166">Listet alle Datenträger unter einem Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="9e980-166">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.RevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.RevokeAccessAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;RevokeAccessAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-168">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-169">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-169">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-171">Hebt den Zugriff auf einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-171">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.UpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9e980-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9e980-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9e980-173">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9e980-173">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="9e980-174">Der Name des Datenträgers in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="9e980-174">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="9e980-175">Disk-Objekt im Text des Patch-Vorgangs Datenträger angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e980-175">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9e980-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9e980-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9e980-177">Updates (Patches) einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="9e980-177">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>