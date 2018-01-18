<Type Name="ClustersOperationsExtensions" FullName="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ClustersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ClustersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ClustersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ClustersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1f7b4-101">Erweiterungsmethoden für ClustersOperations.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-101">Extension methods for ClustersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster BeginCreate (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster BeginCreate(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreate(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreate (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-104">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-104">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-105">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-105">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-106">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-106">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1f7b4-107">Die Parameter für die Erstellung des Clusters angeben.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-107">The parameters to provide for cluster creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-108">Fügt einem Cluster hinzu.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-108">Adds a cluster.</span></span> <span data-ttu-id="1f7b4-109">Eine Auflistung von Compute-Knoten um einen Cluster handelt.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-109">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="1f7b4-110">Mehrere Aufträge können auf demselben Cluster ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-110">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; BeginCreateAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; BeginCreateAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;BeginCreateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-112">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-112">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-113">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-113">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-114">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-114">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-115">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-115">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1f7b4-116">Die Parameter für die Erstellung des Clusters angeben.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-116">The parameters to provide for cluster creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-118">Fügt einem Cluster hinzu.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-118">Adds a cluster.</span></span> <span data-ttu-id="1f7b4-119">Eine Auflistung von Compute-Knoten um einen Cluster handelt.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-119">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="1f7b4-120">Mehrere Aufträge können auf demselben Cluster ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-120">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IClustersOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDelete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-122">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-123">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-123">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-124">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-124">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-125">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-125">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-126">Löscht einen Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-126">Deletes a Cluster.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-128">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-128">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-129">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-129">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-130">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-130">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-131">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-131">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-133">Löscht einen Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-133">Deletes a Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster Create (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster Create(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Create(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Create (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-135">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-135">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-136">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-136">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-137">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-137">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-138">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-138">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1f7b4-139">Die Parameter für die Erstellung des Clusters angeben.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-139">The parameters to provide for cluster creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-140">Fügt einem Cluster hinzu.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-140">Adds a cluster.</span></span> <span data-ttu-id="1f7b4-141">Eine Auflistung von Compute-Knoten um einen Cluster handelt.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-141">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="1f7b4-142">Mehrere Aufträge können auf demselben Cluster ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-142">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; CreateAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; CreateAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.CreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-144">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-145">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-145">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-146">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-146">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-147">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-147">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1f7b4-148">Die Parameter für die Erstellung des Clusters angeben.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-148">The parameters to provide for cluster creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-150">Fügt einem Cluster hinzu.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-150">Adds a cluster.</span></span> <span data-ttu-id="1f7b4-151">Eine Auflistung von Compute-Knoten um einen Cluster handelt.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-151">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="1f7b4-152">Mehrere Aufträge können auf demselben Cluster ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-152">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Delete(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IClustersOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Delete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-154">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-154">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-155">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-155">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-156">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-156">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-157">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-157">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-158">Löscht einen Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-158">Deletes a Cluster.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.DeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-160">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-160">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-161">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-161">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-162">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-162">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-163">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-163">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-165">Löscht einen Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-165">Deletes a Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster Get (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster Get(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Get(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IClustersOperations, resourceGroupName As String, clusterName As String) As Cluster" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Get (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-167">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-167">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-168">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-168">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-169">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-169">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-170">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-170">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-171">Ruft Informationen zu dem angegebenen Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-171">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; GetAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; GetAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.GetAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.GetAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-173">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-173">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-174">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-174">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-175">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-175">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-176">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-176">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-178">Ruft Informationen zu dem angegebenen Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-178">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; List (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; List(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.List(Microsoft.Azure.Management.BatchAI.IClustersOperations,Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BatchAI.IClustersOperations * Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.List (operations, clustersListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="clustersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-179">The operations group for this extension method.</span></span>
            </param>
        <param name="clustersListOptions">
            <span data-ttu-id="1f7b4-180">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="1f7b4-180">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-181">Ruft Informationen zu den Clustern, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-181">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListAsync (operations, clustersListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="clustersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-182">The operations group for this extension method.</span></span>
            </param>
        <param name="clustersListOptions">
            <span data-ttu-id="1f7b4-183">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="1f7b4-183">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-184">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-185">Ruft Informationen zu den Clustern, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-185">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroup (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroup(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, clustersListByResourceGroupOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clustersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-187">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clustersListByResourceGroupOptions">
            <span data-ttu-id="1f7b4-188">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="1f7b4-188">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-189">Ruft Informationen zu den Clustern, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-189">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, clustersListByResourceGroupOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clustersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-191">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-191">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clustersListByResourceGroupOptions">
            <span data-ttu-id="1f7b4-192">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="1f7b4-192">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-194">Ruft Informationen zu den Clustern, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-194">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.BatchAI.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1f7b4-196">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-197">Ruft Informationen zu den Clustern, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-197">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1f7b4-199">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-201">Ruft Informationen zu den Clustern, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-201">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListNext (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListNext(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNext(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.BatchAI.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1f7b4-203">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-204">Ruft Informationen zu den Clustern, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-204">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1f7b4-206">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-208">Ruft Informationen zu den Clustern, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-208">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformation">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformation(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformation (operations As IClustersOperations, resourceGroupName As String, clusterName As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformation : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformation (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-210">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-210">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-211">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-211">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-212">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-212">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-213">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-213">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-214">Abrufen der IP-Adresse, Port, der alle Serverknoten im Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-214">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListRemoteLoginInformationAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-216">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-216">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-217">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-217">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-218">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-218">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-219">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-219">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-220">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-221">Abrufen der IP-Adresse, Port, der alle Serverknoten im Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-221">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNext(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformationNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNext : Microsoft.Azure.Management.BatchAI.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-222">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-222">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1f7b4-223">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-223">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-224">Abrufen der IP-Adresse, Port, der alle Serverknoten im Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-224">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNextAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNextAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListRemoteLoginInformationNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-225">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1f7b4-226">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-226">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-228">Abrufen der IP-Adresse, Port, der alle Serverknoten im Cluster an.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-228">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster Update (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster Update(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Update(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterUpdateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Update (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-230">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-230">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-231">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-231">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-232">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-232">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-233">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-233">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1f7b4-234">Zusätzliche Parameter für Cluster aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-234">Additional parameters for cluster update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-235">Aktualisieren der Eigenschaften eines bestimmten Clusters.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-235">Update the properties of a given cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; UpdateAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; UpdateAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.UpdateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1f7b4-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1f7b4-237">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-237">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="1f7b4-238">Der Name des Clusters in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-238">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="1f7b4-239">Clusternamen dürfen nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-239">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="1f7b4-240">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-240">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1f7b4-241">Zusätzliche Parameter für Cluster aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-241">Additional parameters for cluster update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1f7b4-242">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1f7b4-243">Aktualisieren der Eigenschaften eines bestimmten Clusters.</span><span class="sxs-lookup"><span data-stu-id="1f7b4-243">Update the properties of a given cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>