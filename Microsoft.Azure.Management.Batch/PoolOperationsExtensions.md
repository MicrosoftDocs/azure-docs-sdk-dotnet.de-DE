<Type Name="PoolOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.PoolOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PoolOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PoolOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.PoolOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PoolOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PoolOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e2ca0-101">Erweiterungsmethoden für PoolOperations.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-101">Extension methods for PoolOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool BeginCreate (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool BeginCreate(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String, parameters As Pool, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Pool" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-103">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-104">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-104">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-105">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-105">The pool name.</span></span> <span data-ttu-id="e2ca0-106">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-106">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e2ca0-107">Zusätzliche Parameter für die Erstellung von Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-107">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="e2ca0-108">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-108">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="e2ca0-109">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn der Pool bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-109">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="e2ca0-110">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-110">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="e2ca0-111">Legen Sie auf "\*" um einen neuen Pool erstellt werden, sondern um zu verhindern, aktualisieren einen vorhandenen Pool zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-111">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="e2ca0-112">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-112">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-113">Erstellt einen neuen Pool in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-113">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;BeginCreateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-115">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-115">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-116">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-116">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-117">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-117">The pool name.</span></span> <span data-ttu-id="e2ca0-118">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-118">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e2ca0-119">Zusätzliche Parameter für die Erstellung von Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-119">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="e2ca0-120">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-120">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="e2ca0-121">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn der Pool bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-121">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="e2ca0-122">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-122">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="e2ca0-123">Legen Sie auf "\*" um einen neuen Pool erstellt werden, sondern um zu verhindern, aktualisieren einen vorhandenen Pool zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-123">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="e2ca0-124">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-124">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-126">Erstellt einen neuen Pool in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-126">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As PoolDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-128">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-128">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-129">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-129">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-130">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-130">The pool name.</span></span> <span data-ttu-id="e2ca0-131">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-131">This must be unique within the account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-132">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-132">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-134">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-134">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-135">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-135">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-136">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-136">The pool name.</span></span> <span data-ttu-id="e2ca0-137">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-137">This must be unique within the account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-139">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-139">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool Create (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool Create(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Create(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String, parameters As Pool, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Pool" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Create (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-141">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-141">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-142">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-142">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-143">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-143">The pool name.</span></span> <span data-ttu-id="e2ca0-144">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-144">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e2ca0-145">Zusätzliche Parameter für die Erstellung von Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-145">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="e2ca0-146">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-146">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="e2ca0-147">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn der Pool bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-147">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="e2ca0-148">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-148">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="e2ca0-149">Legen Sie auf "\*" um einen neuen Pool erstellt werden, sondern um zu verhindern, aktualisieren einen vorhandenen Pool zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-149">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="e2ca0-150">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-150">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-151">Erstellt einen neuen Pool in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-151">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; CreateAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; CreateAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-153">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-153">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-154">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-154">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-155">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-155">The pool name.</span></span> <span data-ttu-id="e2ca0-156">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-156">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e2ca0-157">Zusätzliche Parameter für die Erstellung von Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-157">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="e2ca0-158">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-158">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="e2ca0-159">Der Wert "\*" können verwendet werden, um die Operation angewendet werden, wenn der Pool bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-159">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="e2ca0-160">Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-160">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="e2ca0-161">Legen Sie auf "\*" um einen neuen Pool erstellt werden, sondern um zu verhindern, aktualisieren einen vorhandenen Pool zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-161">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="e2ca0-162">Andere Werte werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-162">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-164">Erstellt einen neuen Pool in das angegebene Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-164">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As PoolDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Delete (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-166">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-166">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-167">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-167">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-168">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-168">The pool name.</span></span> <span data-ttu-id="e2ca0-169">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-169">This must be unique within the account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-170">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-170">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-172">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-172">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-173">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-173">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-174">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-174">The pool name.</span></span> <span data-ttu-id="e2ca0-175">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-175">This must be unique within the account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-177">Löscht den angegebenen Pool.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-177">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool DisableAutoScale (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool DisableAutoScale(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScale(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DisableAutoScale (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As Pool" />
      <MemberSignature Language="F#" Value="static member DisableAutoScale : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScale (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-179">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-179">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-180">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-180">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-181">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-181">The pool name.</span></span> <span data-ttu-id="e2ca0-182">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-182">This must be unique within the account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-183">Deaktiviert die automatische Skalierung für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-183">Disables automatic scaling for a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; DisableAutoScaleAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; DisableAutoScaleAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScaleAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAutoScaleAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScaleAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;DisableAutoScaleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-185">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-185">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-186">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-186">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-187">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-187">The pool name.</span></span> <span data-ttu-id="e2ca0-188">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-188">This must be unique within the account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-190">Deaktiviert die automatische Skalierung für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-190">Disables automatic scaling for a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool Get (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool Get(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Get(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As Pool" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Get (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-192">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-192">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-193">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-193">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-194">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-194">The pool name.</span></span> <span data-ttu-id="e2ca0-195">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-195">This must be unique within the account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-196">Ruft Informationen über den angegebenen Pool ab.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-196">Gets information about the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; GetAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; GetAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-198">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-198">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-199">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-199">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-200">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-200">The pool name.</span></span> <span data-ttu-id="e2ca0-201">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-201">This must be unique within the account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-202">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-203">Ruft Informationen über den angegebenen Pool ab.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-203">Gets information about the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccount (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccount(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccount(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccount (operations As IPoolOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null, Optional select As String = null, Optional filter As String = null) As IPage(Of Pool)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccount : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccount (operations, resourceGroupName, accountName, maxresults, select, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="e2ca0-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-204">The operations group for this extension method.</span></span>
             </param>
        <param name="resourceGroupName">
             <span data-ttu-id="e2ca0-205">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-205">The name of the resource group that contains the Batch account.</span></span>
             </param>
        <param name="accountName">
             <span data-ttu-id="e2ca0-206">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-206">The name of the Batch account.</span></span>
             </param>
        <param name="maxresults">
             <span data-ttu-id="e2ca0-207">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-207">The maximum number of items to return in the response.</span></span>
             </param>
        <param name="select">
             <span data-ttu-id="e2ca0-208">Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-208">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="e2ca0-209">z. B. "Eigenschaften/ProvisioningState".</span><span class="sxs-lookup"><span data-stu-id="e2ca0-209">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="e2ca0-210">Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-210">Only top level properties under properties/ are valid for selection.</span></span>
             </param>
        <param name="filter">
             <span data-ttu-id="e2ca0-211">OData-Filterausdruck.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-211">OData filter expression.</span></span> <span data-ttu-id="e2ca0-212">Gültige Eigenschaften für das Filtern lauten:</span><span class="sxs-lookup"><span data-stu-id="e2ca0-212">Valid properties for filtering are:</span></span>
            
             <span data-ttu-id="e2ca0-213">Benennen von Eigenschaften/AllocationState Eigenschaften/AllocationStateTransitionTime Eigenschaften/CreationTime-Eigenschaften/ProvisioningState-Eigenschaften/ProvisioningStateTransitionTime Eigenschaften/LastModified-Eigenschaften/VmSize Eigenschaften / InterNodeCommunication Eigenschaften/ScaleSettings/automatische Skalierung Eigenschaften/ScaleSettings/fixedScale</span><span class="sxs-lookup"><span data-stu-id="e2ca0-213">name properties/allocationState properties/allocationStateTransitionTime properties/creationTime properties/provisioningState properties/provisioningStateTransitionTime properties/lastModified properties/vmSize properties/interNodeCommunication properties/scaleSettings/autoScale properties/scaleSettings/fixedScale</span></span>
             </param>
        <summary>
             <span data-ttu-id="e2ca0-214">Listet alle Pools im angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-214">Lists all of the pools in the specified account.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * Nullable&lt;int&gt; * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountAsync (operations, resourceGroupName, accountName, maxresults, select, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;ListByBatchAccountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="e2ca0-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-215">The operations group for this extension method.</span></span>
             </param>
        <param name="resourceGroupName">
             <span data-ttu-id="e2ca0-216">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-216">The name of the resource group that contains the Batch account.</span></span>
             </param>
        <param name="accountName">
             <span data-ttu-id="e2ca0-217">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-217">The name of the Batch account.</span></span>
             </param>
        <param name="maxresults">
             <span data-ttu-id="e2ca0-218">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-218">The maximum number of items to return in the response.</span></span>
             </param>
        <param name="select">
             <span data-ttu-id="e2ca0-219">Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-219">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="e2ca0-220">z. B. "Eigenschaften/ProvisioningState".</span><span class="sxs-lookup"><span data-stu-id="e2ca0-220">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="e2ca0-221">Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-221">Only top level properties under properties/ are valid for selection.</span></span>
             </param>
        <param name="filter">
             <span data-ttu-id="e2ca0-222">OData-Filterausdruck.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-222">OData filter expression.</span></span> <span data-ttu-id="e2ca0-223">Gültige Eigenschaften für das Filtern lauten:</span><span class="sxs-lookup"><span data-stu-id="e2ca0-223">Valid properties for filtering are:</span></span>
            
             <span data-ttu-id="e2ca0-224">Benennen von Eigenschaften/AllocationState Eigenschaften/AllocationStateTransitionTime Eigenschaften/CreationTime-Eigenschaften/ProvisioningState-Eigenschaften/ProvisioningStateTransitionTime Eigenschaften/LastModified-Eigenschaften/VmSize Eigenschaften / InterNodeCommunication Eigenschaften/ScaleSettings/automatische Skalierung Eigenschaften/ScaleSettings/fixedScale</span><span class="sxs-lookup"><span data-stu-id="e2ca0-224">name properties/allocationState properties/allocationStateTransitionTime properties/creationTime properties/provisioningState properties/provisioningStateTransitionTime properties/lastModified properties/vmSize properties/interNodeCommunication properties/scaleSettings/autoScale properties/scaleSettings/fixedScale</span></span>
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="e2ca0-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-225">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="e2ca0-226">Listet alle Pools im angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-226">Lists all of the pools in the specified account.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccountNext (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccountNext(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNext(Microsoft.Azure.Management.Batch.IPoolOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccountNext (operations As IPoolOperations, nextPageLink As String) As IPage(Of Pool)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNext : Microsoft.Azure.Management.Batch.IPoolOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-227">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e2ca0-228">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-228">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-229">Listet alle Pools im angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-229">Lists all of the pools in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountNextAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountNextAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNextAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNextAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;ListByBatchAccountNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-230">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-230">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e2ca0-231">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-231">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-232">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-233">Listet alle Pools im angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-233">Lists all of the pools in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool StopResize (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool StopResize(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResize(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StopResize (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As Pool" />
      <MemberSignature Language="F#" Value="static member StopResize : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResize (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-235">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-235">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-236">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-236">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-237">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-237">The pool name.</span></span> <span data-ttu-id="e2ca0-238">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-238">This must be unique within the account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-239">Beendet einen aktiven größenänderungsvorgang für den Pool an.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-239">Stops an ongoing resize operation on the pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e2ca0-240">Dies wird den Pool nicht auf den ursprünglichen Zustand vor der Größenänderung wiederhergestellt: nur beendet wird, keine weiteren Änderungen vorgenommen werden, und der Pool behält den aktuellen Zustand.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-240">This does not restore the pool to its previous state before the resize operation: it only stops any further changes being made, and the pool maintains its current state.</span></span> <span data-ttu-id="e2ca0-241">Nach dem Beenden stabilisiert der Pool an die Anzahl der Knoten, den sie an, wenn der Beendigungsvorgang abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-241">After stopping, the pool stabilizes at the number of nodes it was at when the stop operation was done.</span></span> <span data-ttu-id="e2ca0-242">Während des Beendigungsvorgangs ändert den Zuordnungsstatus des Pools zunächst zu beenden und dann zu gleichmäßig.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-242">During the stop operation, the pool allocation state changes first to stopping and then to steady.</span></span> <span data-ttu-id="e2ca0-243">Ein größenänderungsvorgang muss eine explizite Resize Pool-Anfrage nicht. Diese API kann auch verwendet werden, auf die anfängliche Größe des Pools anhalten, wenn es erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-243">A resize operation need not be an explicit resize pool request; this API can also be used to halt the initial sizing of the pool when it is created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; StopResizeAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; StopResizeAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResizeAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopResizeAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResizeAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;StopResizeAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-244">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-244">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-245">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-245">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-246">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-246">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-247">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-247">The pool name.</span></span> <span data-ttu-id="e2ca0-248">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-248">This must be unique within the account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-249">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-250">Beendet einen aktiven größenänderungsvorgang für den Pool an.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-250">Stops an ongoing resize operation on the pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e2ca0-251">Dies wird den Pool nicht auf den ursprünglichen Zustand vor der Größenänderung wiederhergestellt: nur beendet wird, keine weiteren Änderungen vorgenommen werden, und der Pool behält den aktuellen Zustand.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-251">This does not restore the pool to its previous state before the resize operation: it only stops any further changes being made, and the pool maintains its current state.</span></span> <span data-ttu-id="e2ca0-252">Nach dem Beenden stabilisiert der Pool an die Anzahl der Knoten, den sie an, wenn der Beendigungsvorgang abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-252">After stopping, the pool stabilizes at the number of nodes it was at when the stop operation was done.</span></span> <span data-ttu-id="e2ca0-253">Während des Beendigungsvorgangs ändert den Zuordnungsstatus des Pools zunächst zu beenden und dann zu gleichmäßig.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-253">During the stop operation, the pool allocation state changes first to stopping and then to steady.</span></span> <span data-ttu-id="e2ca0-254">Ein größenänderungsvorgang muss eine explizite Resize Pool-Anfrage nicht. Diese API kann auch verwendet werden, auf die anfängliche Größe des Pools anhalten, wenn es erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-254">A resize operation need not be an explicit resize pool request; this API can also be used to halt the initial sizing of the pool when it is created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool Update (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool Update(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Update(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String, parameters As Pool, Optional ifMatch As String = null) As Pool" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Update (operations, resourceGroupName, accountName, poolName, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-255">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-256">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-256">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-257">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-257">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-258">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-258">The pool name.</span></span> <span data-ttu-id="e2ca0-259">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-259">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e2ca0-260">Pooleigenschaften, die aktualisiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-260">Pool properties that should be updated.</span></span> <span data-ttu-id="e2ca0-261">Eigenschaften, die bereitgestellt werden aktualisiert werden, eine Eigenschaft nicht angegeben wird nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-261">Properties that are supplied will be updated, any property not supplied will be unchanged.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="e2ca0-262">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-262">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="e2ca0-263">Dieser Wert ausgelassen oder auf festgelegt werden kann "\*" um den Vorgang ohne Bedingung anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-263">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-264">Aktualisiert die Eigenschaften eines vorhandenen Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-264">Updates the properties of an existing pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e2ca0-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e2ca0-266">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-266">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e2ca0-267">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-267">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="e2ca0-268">Der Name des Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-268">The pool name.</span></span> <span data-ttu-id="e2ca0-269">Dies muss im Konto eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-269">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e2ca0-270">Pooleigenschaften, die aktualisiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-270">Pool properties that should be updated.</span></span> <span data-ttu-id="e2ca0-271">Eigenschaften, die bereitgestellt werden aktualisiert werden, eine Eigenschaft nicht angegeben wird nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-271">Properties that are supplied will be updated, any property not supplied will be unchanged.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="e2ca0-272">Die entitätszustandsversion (ETag) Pool zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-272">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="e2ca0-273">Dieser Wert ausgelassen oder auf festgelegt werden kann "\*" um den Vorgang ohne Bedingung anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-273">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2ca0-274">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-274">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2ca0-275">Aktualisiert die Eigenschaften eines vorhandenen Pools.</span><span class="sxs-lookup"><span data-stu-id="e2ca0-275">Updates the properties of an existing pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>