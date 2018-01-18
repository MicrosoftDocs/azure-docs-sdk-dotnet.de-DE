<Type Name="ReplicationsOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ReplicationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ReplicationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ReplicationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ReplicationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="073f1-101">Erweiterungsmethoden für ReplicationsOperations.</span><span class="sxs-lookup"><span data-stu-id="073f1-101">Extension methods for ReplicationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginCreate (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginCreate(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, location As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreate (operations, resourceGroupName, registryName, replicationName, location, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-103">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-103">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-104">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-104">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-105">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-105">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="073f1-106">Der Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-106">The location of the resource.</span></span> <span data-ttu-id="073f1-107">Dies kann nicht geändert werden, nachdem die Ressource erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="073f1-107">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-108">Die Tags der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-108">The tags of the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-109">Erstellt eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-109">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginCreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginCreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, registryName, replicationName, location, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;BeginCreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-111">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-111">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-112">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-112">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-113">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-113">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="073f1-114">Der Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-114">The location of the resource.</span></span> <span data-ttu-id="073f1-115">Dies kann nicht geändert werden, nachdem die Ressource erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="073f1-115">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-116">Die Tags der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-116">The tags of the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-118">Erstellt eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-118">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDelete (operations, resourceGroupName, registryName, replicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-120">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-120">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-121">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-121">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-122">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-122">The name of the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-123">Löscht eine Replikation aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="073f1-123">Deletes a replication from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, registryName, replicationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-125">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-125">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-126">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-126">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-127">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-127">The name of the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-129">Löscht eine Replikation aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="073f1-129">Deletes a replication from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginUpdate (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginUpdate(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdate (operations, resourceGroupName, registryName, replicationName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-131">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-131">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-132">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-132">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-133">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-133">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-134">Die Tags für die Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-134">The tags for the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-135">Aktualisiert eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-135">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginUpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginUpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, registryName, replicationName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-137">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-137">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-138">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-138">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-139">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-139">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-140">Die Tags für die Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-140">The tags for the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-142">Aktualisiert eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-142">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication Create (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication Create(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Create(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, location As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Create (operations, resourceGroupName, registryName, replicationName, location, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-144">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-144">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-145">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-145">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-146">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-146">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="073f1-147">Der Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-147">The location of the resource.</span></span> <span data-ttu-id="073f1-148">Dies kann nicht geändert werden, nachdem die Ressource erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="073f1-148">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-149">Die Tags der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-149">The tags of the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-150">Erstellt eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-150">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; CreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; CreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.CreateAsync (operations, resourceGroupName, registryName, replicationName, location, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-152">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-152">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-153">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-153">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-154">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-154">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="073f1-155">Der Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-155">The location of the resource.</span></span> <span data-ttu-id="073f1-156">Dies kann nicht geändert werden, nachdem die Ressource erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="073f1-156">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-157">Die Tags der Ressource.</span><span class="sxs-lookup"><span data-stu-id="073f1-157">The tags of the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-159">Erstellt eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-159">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Delete(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Delete (operations, resourceGroupName, registryName, replicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-161">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-161">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-162">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-162">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-163">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-163">The name of the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-164">Löscht eine Replikation aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="073f1-164">Deletes a replication from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.DeleteAsync (operations, resourceGroupName, registryName, replicationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-166">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-166">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-167">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-167">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-168">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-168">The name of the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-170">Löscht eine Replikation aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="073f1-170">Deletes a replication from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication Get (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication Get(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Get(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String) As Replication" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Get (operations, resourceGroupName, registryName, replicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-172">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-172">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-173">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-173">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-174">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-174">The name of the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-175">Ruft die Eigenschaften der angegebenen Replikation ab.</span><span class="sxs-lookup"><span data-stu-id="073f1-175">Gets the properties of the specified replication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; GetAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; GetAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.GetAsync (operations, resourceGroupName, registryName, replicationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-177">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-177">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-178">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-178">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-179">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-179">The name of the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-181">Ruft die Eigenschaften der angegebenen Replikation ab.</span><span class="sxs-lookup"><span data-stu-id="073f1-181">Gets the properties of the specified replication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; List (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; List(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.List(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IReplicationsOperations, resourceGroupName As String, registryName As String) As IPage(Of Replication)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.List (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-183">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-183">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-184">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-184">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-185">Listet alle Replikationen für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="073f1-185">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-187">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-187">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-188">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-188">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-190">Listet alle Replikationen für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="073f1-190">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; ListNext (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; ListNext(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNext(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IReplicationsOperations, nextPageLink As String) As IPage(Of Replication)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="073f1-192">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="073f1-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-193">Listet alle Replikationen für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="073f1-193">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="073f1-195">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="073f1-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-197">Listet alle Replikationen für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="073f1-197">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication Update (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication Update(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Update(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Update (operations, resourceGroupName, registryName, replicationName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-199">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-199">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-200">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-200">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-201">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-201">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-202">Die Tags für die Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-202">The tags for the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-203">Aktualisiert eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-203">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; UpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; UpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.UpdateAsync (operations, resourceGroupName, registryName, replicationName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="073f1-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="073f1-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="073f1-205">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="073f1-205">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="073f1-206">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="073f1-206">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="073f1-207">Der Name der Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-207">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="073f1-208">Die Tags für die Replikation.</span><span class="sxs-lookup"><span data-stu-id="073f1-208">The tags for the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="073f1-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="073f1-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="073f1-210">Aktualisiert eine Replikation für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="073f1-210">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>