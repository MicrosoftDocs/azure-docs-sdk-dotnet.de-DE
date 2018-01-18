<Type Name="AppServiceEnvironmentsOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceEnvironmentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironmentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4bd48-101">Erweiterungsmethoden für AppServiceEnvironmentsOperations.</span><span class="sxs-lookup"><span data-stu-id="4bd48-101">Extension methods for AppServiceEnvironmentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource BeginCreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource BeginCreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, hostingEnvironmentEnvelope As AppServiceEnvironmentResource) As AppServiceEnvironmentResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, name, hostingEnvironmentEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-104">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-104">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="4bd48-105">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-105">Configuration details of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-106">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-106">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-107">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-107">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-109">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-109">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-110">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-110">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="4bd48-111">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-111">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-113">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-113">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-114">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-114">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateMultiRolePool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource BeginCreateOrUpdateMultiRolePool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource BeginCreateOrUpdateMultiRolePool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateMultiRolePool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, multiRolePoolEnvelope As WorkerPoolResource) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateMultiRolePool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePool (operations, resourceGroupName, name, multiRolePoolEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-116">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-116">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-117">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-117">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="4bd48-118">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-118">Properties of the multi-role pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-119">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-119">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-120">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-120">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; BeginCreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; BeginCreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateMultiRolePoolAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-122">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-123">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-123">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="4bd48-124">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-124">Properties of the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-126">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-126">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-127">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-127">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWorkerPool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource BeginCreateOrUpdateWorkerPool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource BeginCreateOrUpdateWorkerPool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWorkerPool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String, workerPoolEnvelope As WorkerPoolResource) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWorkerPool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPool (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-129">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-129">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-130">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-130">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-131">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-131">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="4bd48-132">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-132">Properties of the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-133">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-133">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-134">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-134">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; BeginCreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; BeginCreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateWorkerPoolAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-136">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-136">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-137">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-137">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-138">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-138">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="4bd48-139">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-139">Properties of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-141">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-141">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-142">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-142">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, Optional forceDelete As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginDelete (operations, resourceGroupName, name, forceDelete)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-144">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-145">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-145">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="4bd48-146">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den Löschvorgang zu erzwingen, auch wenn die App Service-Umgebung Ressourcen enthält.</span><span class="sxs-lookup"><span data-stu-id="4bd48-146">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="4bd48-147">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-147">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-148">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-148">Delete an App Service Environment.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="4bd48-149">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-149">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-151">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-152">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-152">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="4bd48-153">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den Löschvorgang zu erzwingen, auch wenn die App Service-Umgebung Ressourcen enthält.</span><span class="sxs-lookup"><span data-stu-id="4bd48-153">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="4bd48-154">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-154">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-156">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-156">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-157">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-157">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResume">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginResume (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginResume(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResume(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginResume (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member BeginResume : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResume (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-159">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-160">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-160">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-161">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-161">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-162">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-162">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginResumeAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginResumeAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-164">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-164">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-165">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-165">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-167">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-167">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-168">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-168">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginResumeNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginResumeNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResumeNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginResumeNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member BeginResumeNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResumeNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-169">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-170">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-170">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-171">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-171">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-172">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-172">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginResumeNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginResumeNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeNextAsync&gt;d__137))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-176">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-176">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-177">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-177">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginSuspend (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginSuspend(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspend(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginSuspend (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member BeginSuspend : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspend (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-179">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-179">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-180">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-180">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-181">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-181">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-182">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-182">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginSuspendAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginSuspendAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-184">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-184">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-185">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-185">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-187">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-187">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-188">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-188">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginSuspendNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; BeginSuspendNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginSuspendNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-189">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-190">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-190">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-191">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-191">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-192">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-192">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginSuspendNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; BeginSuspendNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendNextAsync&gt;d__139))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-193">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-194">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-194">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-195">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-196">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-196">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-197">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-197">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource CreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource CreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, hostingEnvironmentEnvelope As AppServiceEnvironmentResource) As AppServiceEnvironmentResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, name, hostingEnvironmentEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-199">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-199">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-200">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-200">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="4bd48-201">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-201">Configuration details of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-202">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-202">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-203">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-203">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-205">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-205">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-206">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-206">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="4bd48-207">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-207">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-209">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-209">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-210">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-210">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateMultiRolePool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource CreateOrUpdateMultiRolePool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource CreateOrUpdateMultiRolePool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateMultiRolePool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, multiRolePoolEnvelope As WorkerPoolResource) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateMultiRolePool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePool (operations, resourceGroupName, name, multiRolePoolEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-211">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-211">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-212">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-212">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-213">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-213">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="4bd48-214">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-214">Properties of the multi-role pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-215">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-215">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-216">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-216">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; CreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; CreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateMultiRolePoolAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-217">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-217">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-218">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-218">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-219">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-219">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="4bd48-220">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-220">Properties of the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-222">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-222">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-223">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-223">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWorkerPool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource CreateOrUpdateWorkerPool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource CreateOrUpdateWorkerPool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWorkerPool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String, workerPoolEnvelope As WorkerPoolResource) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWorkerPool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPool (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-225">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-225">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-226">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-226">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-227">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-227">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="4bd48-228">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-228">Properties of the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-229">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-229">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-230">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-230">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; CreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; CreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateWorkerPoolAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-231">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-232">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-232">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-233">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-233">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-234">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-234">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="4bd48-235">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-235">Properties of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-236">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-237">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-237">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-238">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-238">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Delete(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, Optional forceDelete As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Delete (operations, resourceGroupName, name, forceDelete)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-239">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-239">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-240">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-240">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-241">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-241">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="4bd48-242">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den Löschvorgang zu erzwingen, auch wenn die App Service-Umgebung Ressourcen enthält.</span><span class="sxs-lookup"><span data-stu-id="4bd48-242">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="4bd48-243">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-243">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-244">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-244">Delete an App Service Environment.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="4bd48-245">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-245">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-246">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-246">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-247">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-247">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-248">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-248">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="4bd48-249">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den Löschvorgang zu erzwingen, auch wenn die App Service-Umgebung Ressourcen enthält.</span><span class="sxs-lookup"><span data-stu-id="4bd48-249">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="4bd48-250">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-250">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-251">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-252">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-252">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-253">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-253">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource Get (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource Get(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As AppServiceEnvironmentResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-254">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-255">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-255">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-256">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-256">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-257">Rufen Sie die Eigenschaften der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-257">Get the properties of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-258">Rufen Sie die Eigenschaften der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-258">Get the properties of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; GetAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; GetAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-259">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-259">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-260">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-260">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-261">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-261">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-262">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-263">Rufen Sie die Eigenschaften der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-263">Get the properties of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-264">Rufen Sie die Eigenschaften der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-264">Get the properties of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDiagnosticsItem">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics GetDiagnosticsItem (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics GetDiagnosticsItem(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItem(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDiagnosticsItem (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, diagnosticsName As String) As HostingEnvironmentDiagnostics" />
      <MemberSignature Language="F#" Value="static member GetDiagnosticsItem : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItem (operations, resourceGroupName, name, diagnosticsName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="diagnosticsName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-266">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-266">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-267">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-267">Name of the App Service Environment.</span></span>
            </param>
        <param name="diagnosticsName">
            <span data-ttu-id="4bd48-268">Der Name des Diagnose-Elements.</span><span class="sxs-lookup"><span data-stu-id="4bd48-268">Name of the diagnostics item.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-269">Ruft ein Element für die Diagnose für App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-269">Get a diagnostics item for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-270">Ruft ein Element für die Diagnose für App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-270">Get a diagnostics item for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDiagnosticsItemAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt; GetDiagnosticsItemAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt; GetDiagnosticsItemAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDiagnosticsItemAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync (operations, resourceGroupName, name, diagnosticsName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;GetDiagnosticsItemAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="diagnosticsName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-271">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-272">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-272">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-273">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-273">Name of the App Service Environment.</span></span>
            </param>
        <param name="diagnosticsName">
            <span data-ttu-id="4bd48-274">Der Name des Diagnose-Elements.</span><span class="sxs-lookup"><span data-stu-id="4bd48-274">Name of the diagnostics item.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-275">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-275">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-276">Ruft ein Element für die Diagnose für App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-276">Get a diagnostics item for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-277">Ruft ein Element für die Diagnose für App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-277">Get a diagnostics item for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMultiRolePool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource GetMultiRolePool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource GetMultiRolePool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetMultiRolePool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member GetMultiRolePool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePool (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-278">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-278">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-279">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-279">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-280">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-280">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-281">Rufen Sie die Eigenschaften eines Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-281">Get properties of a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-282">Rufen Sie die Eigenschaften eines Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-282">Get properties of a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; GetMultiRolePoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; GetMultiRolePoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMultiRolePoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;GetMultiRolePoolAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-283">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-284">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-284">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-285">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-285">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-286">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-286">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-287">Rufen Sie die Eigenschaften eines Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-287">Get properties of a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-288">Rufen Sie die Eigenschaften eines Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-288">Get properties of a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWorkerPool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource GetWorkerPool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource GetWorkerPool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetWorkerPool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetWorkerPool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member GetWorkerPool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetWorkerPool (operations, resourceGroupName, name, workerPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-289">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-289">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-290">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-290">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-291">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-291">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-292">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-292">Name of the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-293">Rufen Sie die Eigenschaften eines Pools mit Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="4bd48-293">Get properties of a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-294">Rufen Sie die Eigenschaften eines Pools mit Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="4bd48-294">Get properties of a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; GetWorkerPoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; GetWorkerPoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetWorkerPoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;GetWorkerPoolAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-295">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-295">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-296">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-296">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-297">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-297">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-298">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-298">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-299">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-300">Rufen Sie die Eigenschaften eines Pools mit Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="4bd48-300">Get properties of a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-301">Rufen Sie die Eigenschaften eines Pools mit Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="4bd48-301">Get properties of a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; List (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; List(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAppServiceEnvironmentsOperations) As IPage(Of AppServiceEnvironmentResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-302">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-302">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-303">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-303">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-304">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-304">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlans">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListAppServicePlans (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListAppServicePlans(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlans(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAppServicePlans (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlans : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlans (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-305">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-305">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-306">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-306">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-307">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-307">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-308">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-308">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-309">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-309">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAppServicePlansAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAppServicePlansAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-310">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-310">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-311">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-311">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-312">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-312">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-313">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-313">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-314">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-314">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-315">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-315">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListAppServicePlansNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListAppServicePlansNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAppServicePlansNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-316">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-316">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-317">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-317">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-318">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-318">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-319">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-319">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAppServicePlansNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAppServicePlansNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansNextAsync&gt;d__115))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-320">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-320">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-321">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-321">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-322">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-322">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-323">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-323">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-324">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-324">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-325">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-325">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-326">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-327">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-327">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-328">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-328">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; ListByResourceGroup (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; ListByResourceGroup(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String) As IPage(Of AppServiceEnvironmentResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-329">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-329">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-330">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-330">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-331">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-331">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-332">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-332">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-333">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-333">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-334">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-334">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-335">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-335">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-336">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-336">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-337">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-337">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of AppServiceEnvironmentResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-338">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-338">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-339">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-339">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-340">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-340">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-341">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-341">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-342">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-342">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-343">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-343">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-344">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-345">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-345">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-346">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4bd48-346">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacities">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; ListCapacities (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; ListCapacities(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacities(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCapacities (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of StampCapacity)" />
      <MemberSignature Language="F#" Value="static member ListCapacities : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacities (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-347">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-347">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-348">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-348">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-349">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-349">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-350">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-350">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-351">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-351">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt; ListCapacitiesAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt; ListCapacitiesAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-352">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-352">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-353">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-353">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-354">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-354">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-355">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-355">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-356">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-356">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-357">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-357">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; ListCapacitiesNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; ListCapacitiesNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCapacitiesNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of StampCapacity)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-358">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-358">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-359">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-359">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-360">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-360">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-361">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-361">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesNextAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-362">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-362">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-363">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-363">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-364">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-364">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-365">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-365">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-366">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-366">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDiagnostics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt; ListDiagnostics (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt; ListDiagnostics(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListDiagnostics(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDiagnostics (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IList(Of HostingEnvironmentDiagnostics)" />
      <MemberSignature Language="F#" Value="static member ListDiagnostics : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListDiagnostics (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-367">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-367">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-368">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-368">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-369">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-369">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-370">Abrufen von Diagnoseinformationen für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-370">Get diagnostic information for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-371">Abrufen von Diagnoseinformationen für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-371">Get diagnostic information for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDiagnosticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt; ListDiagnosticsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt; ListDiagnosticsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDiagnosticsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListDiagnosticsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-372">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-372">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-373">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-373">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-374">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-374">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-375">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-375">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-376">Abrufen von Diagnoseinformationen für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-376">Get diagnostic information for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-377">Abrufen von Diagnoseinformationen für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-377">Get diagnostic information for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.MetricDefinition ListMetricDefinitions (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.MetricDefinition ListMetricDefinitions(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitions(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinitions (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As MetricDefinition" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitions : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.MetricDefinition" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitions (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.MetricDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-378">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-378">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-379">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-379">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-380">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-380">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-381">Rufen Sie die globale metrikdefinitionen der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-381">Get global metric definitions of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-382">Rufen Sie die globale metrikdefinitionen der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-382">Get global metric definitions of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt; ListMetricDefinitionsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt; ListMetricDefinitionsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricDefinitionsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-383">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-383">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-384">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-384">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-385">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-385">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-386">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-386">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-387">Rufen Sie die globale metrikdefinitionen der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-387">Get global metric definitions of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-388">Rufen Sie die globale metrikdefinitionen der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-388">Get global metric definitions of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetrics (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetrics(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetrics(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, Optional details As Nullable(Of Boolean) = null, Optional filter As String = null) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetrics (operations, resourceGroupName, name, details, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-389">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-389">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-390">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-390">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-391">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-391">Name of the App Service Environment.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-392">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-392">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-393">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-393">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-394">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-394">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-395">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-395">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-396">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-396">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-397">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-397">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-398">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-398">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-399">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-399">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-400">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-400">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-401">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-401">Name of the App Service Environment.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-402">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-402">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-403">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-403">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-404">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-404">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-405">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-405">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-406">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-406">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-407">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-407">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-408">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-408">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-409">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-409">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetricsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetricsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-410">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-410">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-411">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-411">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-412">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-412">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-413">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-413">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-414">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-414">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-415">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-415">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-416">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-416">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-417">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-417">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-418">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-418">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRoleMetricDefinitions (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRoleMetricDefinitions(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitions(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRoleMetricDefinitions (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitions : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitions (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-419">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-419">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-420">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-420">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-421">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-421">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-422">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-422">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-423">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-423">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-424">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-424">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-425">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-425">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-426">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-426">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-427">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-427">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-428">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-428">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-429">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-429">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRoleMetricDefinitionsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRoleMetricDefinitionsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRoleMetricDefinitionsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-430">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-430">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-431">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-431">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-432">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-432">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-433">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-433">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsNextAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-434">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-434">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-435">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-435">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-436">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-436">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-437">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-437">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-438">Rufen Sie die metrikdefinitionen für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-438">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRoleMetrics (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime = null, string endTime = null, string timeGrain = null, Nullable&lt;bool&gt; details = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRoleMetrics(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime, string endTime, string timeGrain, valuetype System.Nullable`1&lt;bool&gt; details, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetrics(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRoleMetrics (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, Optional startTime As String = null, Optional endTime As String = null, Optional timeGrain As String = null, Optional details As Nullable(Of Boolean) = null, Optional filter As String = null) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetrics : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetrics (operations, resourceGroupName, name, startTime, endTime, timeGrain, details, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-439">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-439">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-440">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-440">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-441">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-441">Name of the App Service Environment.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="4bd48-442">Der Anfangszeit der Metriken Abfrage.</span><span class="sxs-lookup"><span data-stu-id="4bd48-442">Beginning time of the metrics query.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="4bd48-443">Beendigungszeit der Abfrage Metriken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-443">End time of the metrics query.</span></span>
            </param>
        <param name="timeGrain">
            <span data-ttu-id="4bd48-444">Zeitgranularität der Metriken Abfrage.</span><span class="sxs-lookup"><span data-stu-id="4bd48-444">Time granularity of the metrics query.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-445">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-445">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-446">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-446">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-447">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-447">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-448">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-448">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-449">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-449">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-450">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-450">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-451">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-451">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime = null, string endTime = null, string timeGrain = null, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime, string endTime, string timeGrain, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync (operations, resourceGroupName, name, startTime, endTime, timeGrain, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-452">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-452">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-453">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-453">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-454">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-454">Name of the App Service Environment.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="4bd48-455">Der Anfangszeit der Metriken Abfrage.</span><span class="sxs-lookup"><span data-stu-id="4bd48-455">Beginning time of the metrics query.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="4bd48-456">Beendigungszeit der Abfrage Metriken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-456">End time of the metrics query.</span></span>
            </param>
        <param name="timeGrain">
            <span data-ttu-id="4bd48-457">Zeitgranularität der Metriken Abfrage.</span><span class="sxs-lookup"><span data-stu-id="4bd48-457">Time granularity of the metrics query.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-458">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-458">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-459">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-459">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-460">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-460">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-461">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-461">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-462">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-462">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-463">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-463">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-464">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-464">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-465">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-465">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRoleMetricsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRoleMetricsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRoleMetricsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-466">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-466">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-467">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-467">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-468">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-468">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-469">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-469">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsNextAsync&gt;d__107))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-470">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-470">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-471">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-471">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-472">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-472">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-473">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-473">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-474">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-474">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRolePoolInstanceMetricDefinitions (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRolePoolInstanceMetricDefinitions(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitions(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePoolInstanceMetricDefinitions (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, instance As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitions : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitions (operations, resourceGroupName, name, instance)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-475">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-475">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-476">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-476">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-477">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-477">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-478">Der Name der Instanz im Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-478">Name of the instance in the multi-role pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-479">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-479">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-480">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-480">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-481">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-481">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-482">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-482">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-483">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-483">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-484">Der Name der Instanz im Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-484">Name of the instance in the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-485">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-485">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-486">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-486">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-487">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-487">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRolePoolInstanceMetricDefinitionsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMultiRolePoolInstanceMetricDefinitionsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePoolInstanceMetricDefinitionsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-488">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-488">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-489">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-489">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-490">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-490">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-491">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-491">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsNextAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-492">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-492">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-493">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-493">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-494">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-494">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-495">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-495">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-496">Rufen Sie metrikdefinitionen für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-496">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRolePoolInstanceMetrics (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, Nullable&lt;bool&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRolePoolInstanceMetrics(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Nullable`1&lt;bool&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetrics(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePoolInstanceMetrics (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, instance As String, Optional details As Nullable(Of Boolean) = null) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetrics : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetrics (operations, resourceGroupName, name, instance, details)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-497">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-497">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-498">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-498">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-499">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-499">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-500">Der Name der Instanz im Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-500">Name of the instance in the multi-role pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-501">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-501">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-502">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-502">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-503">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-503">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-504">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-504">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, Nullable&lt;bool&gt; details = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Nullable`1&lt;bool&gt; details, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync (operations, resourceGroupName, name, instance, details, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-505">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-505">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-506">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-506">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-507">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-507">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-508">Der Name der Instanz im Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-508">Name of the instance in the multi-role pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-509">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-509">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-510">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-510">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-511">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-511">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-512">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-512">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-513">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-513">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRolePoolInstanceMetricsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMultiRolePoolInstanceMetricsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePoolInstanceMetricsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-514">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-514">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-515">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-515">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-516">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-516">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-517">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-517">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsNextAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-518">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-518">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-519">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-519">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-520">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-520">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-521">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-521">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-522">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-522">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePools">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListMultiRolePools (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListMultiRolePools(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePools(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePools (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of WorkerPoolResource)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePools : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePools (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-523">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-523">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-524">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-524">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-525">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-525">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-526">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-526">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-527">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-527">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListMultiRolePoolsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListMultiRolePoolsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-528">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-528">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-529">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-529">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-530">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-530">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-531">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-531">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-532">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-532">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-533">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-533">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListMultiRolePoolSkus (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListMultiRolePoolSkus(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkus(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePoolSkus (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of SkuInfo)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkus : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkus (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-534">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-534">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-535">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-535">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-536">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-536">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-537">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-537">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-538">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-538">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-539">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-539">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-540">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-540">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-541">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-541">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-542">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-542">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-543">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-543">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-544">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-544">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListMultiRolePoolSkusNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListMultiRolePoolSkusNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePoolSkusNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of SkuInfo)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-545">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-545">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-546">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-546">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-547">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-547">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-548">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-548">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusNextAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-549">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-549">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-550">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-550">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-551">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-551">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-552">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-552">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-553">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-553">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListMultiRolePoolsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListMultiRolePoolsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRolePoolsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of WorkerPoolResource)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-554">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-554">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-555">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-555">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-556">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-556">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-557">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-557">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListMultiRolePoolsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListMultiRolePoolsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsNextAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-558">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-558">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-559">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-559">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-560">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-560">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-561">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-561">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-562">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-562">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsages">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListMultiRoleUsages (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListMultiRoleUsages(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsages(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRoleUsages (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of Usage)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsages : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsages (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-563">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-563">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-564">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-564">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-565">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-565">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-566">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-566">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-567">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-567">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-568">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-568">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-569">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-569">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-570">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-570">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-571">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-571">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-572">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-572">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-573">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-573">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListMultiRoleUsagesNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListMultiRoleUsagesNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMultiRoleUsagesNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of Usage)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-574">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-574">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-575">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-575">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-576">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-576">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-577">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-577">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesNextAsync&gt;d__111))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-578">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-578">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-579">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-579">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-580">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-580">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-581">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-581">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-582">Abrufen von nutzungsmetriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-582">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; ListNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; ListNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of AppServiceEnvironmentResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-583">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-583">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-584">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-584">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-585">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-585">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-586">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-586">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListNextAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-587">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-587">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-588">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-588">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-589">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-589">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-590">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-590">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-591">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-591">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperations">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt; ListOperations (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Operation&gt; ListOperations(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListOperations(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOperations (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IList(Of Operation)" />
      <MemberSignature Language="F#" Value="static member ListOperations : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListOperations (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-592">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-592">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-593">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-593">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-594">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-594">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-595">Listen Sie alle derzeit ausgeführten Vorgänge für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-595">List all currently running operations on the App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-596">Listen Sie alle derzeit ausgeführten Vorgänge für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-596">List all currently running operations on the App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt; ListOperationsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt; ListOperationsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListOperationsAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-597">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-597">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-598">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-598">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-599">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-599">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-600">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-600">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-601">Listen Sie alle derzeit ausgeführten Vorgänge für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-601">List all currently running operations on the App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-602">Listen Sie alle derzeit ausgeführten Vorgänge für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-602">List all currently running operations on the App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsages">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsages (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsages(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsages(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsages (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, Optional filter As String = null) As IPage(Of CsmUsageQuota)" />
      <MemberSignature Language="F#" Value="static member ListUsages : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsages (operations, resourceGroupName, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-603">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-603">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-604">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-604">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-605">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-605">Name of the App Service Environment.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-606">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-606">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-607">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-607">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-608">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-608">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-609">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-609">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-610">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-610">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, name, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-611">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-611">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-612">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-612">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-613">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-613">Name of the App Service Environment.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-614">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-614">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-615">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-615">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-616">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-616">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-617">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-617">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-618">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-618">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-619">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-619">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsagesNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsagesNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsagesNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsagesNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of CsmUsageQuota)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsagesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-620">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-620">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-621">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-621">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-622">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-622">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-623">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-623">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesNextAsync&gt;d__121))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-624">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-624">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-625">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-625">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-626">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-626">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-627">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-627">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-628">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-628">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVips">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AddressResponse ListVips (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AddressResponse ListVips(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListVips(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVips (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As AddressResponse" />
      <MemberSignature Language="F#" Value="static member ListVips : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.AddressResponse" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListVips (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AddressResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-629">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-629">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-630">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-630">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-631">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-631">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-632">Get IP-Adressen in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-632">Get IP addresses assigned to an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-633">Get IP-Adressen in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-633">Get IP addresses assigned to an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVipsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt; ListVipsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt; ListVipsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVipsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListVipsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-634">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-634">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-635">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-635">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-636">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-636">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-637">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-637">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-638">Get IP-Adressen in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-638">Get IP addresses assigned to an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-639">Get IP-Adressen in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-639">Get IP addresses assigned to an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebApps">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebApps (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebApps(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebApps(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebApps (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, Optional propertiesToInclude As String = null) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member ListWebApps : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebApps (operations, resourceGroupName, name, propertiesToInclude)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="propertiesToInclude" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-640">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-640">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-641">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-641">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-642">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-642">Name of the App Service Environment.</span></span>
            </param>
        <param name="propertiesToInclude">
            <span data-ttu-id="4bd48-643">Durch Trennzeichen getrennte Liste von app-Eigenschaften eingeschlossen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-643">Comma separated list of app properties to include.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-644">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-644">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-645">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-645">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, propertiesToInclude, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="propertiesToInclude" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-646">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-646">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-647">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-647">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-648">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-648">Name of the App Service Environment.</span></span>
            </param>
        <param name="propertiesToInclude">
            <span data-ttu-id="4bd48-649">Durch Trennzeichen getrennte Liste von app-Eigenschaften eingeschlossen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-649">Comma separated list of app properties to include.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-650">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-650">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-651">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-651">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-652">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-652">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebAppsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebAppsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebAppsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-653">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-653">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-654">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-654">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-655">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-655">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-656">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-656">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__117))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-657">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-657">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-658">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-658">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-659">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-659">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-660">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-660">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-661">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-661">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWebWorkerMetricDefinitions (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWebWorkerMetricDefinitions(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitions(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebWorkerMetricDefinitions (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitions : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitions (operations, resourceGroupName, name, workerPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-662">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-662">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-663">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-663">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-664">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-664">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-665">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-665">Name of the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-666">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-666">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-667">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-667">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-668">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-668">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-669">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-669">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-670">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-670">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-671">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-671">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-672">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-672">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-673">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-673">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-674">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-674">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWebWorkerMetricDefinitionsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWebWorkerMetricDefinitionsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebWorkerMetricDefinitionsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-675">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-675">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-676">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-676">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-677">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-677">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-678">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-678">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsNextAsync&gt;d__129))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-679">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-679">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-680">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-680">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-681">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-681">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-682">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-682">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-683">Rufen Sie die metrikdefinitionen für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-683">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWebWorkerMetrics (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Nullable&lt;bool&gt; details = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWebWorkerMetrics(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Nullable`1&lt;bool&gt; details, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetrics(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebWorkerMetrics (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String, Optional details As Nullable(Of Boolean) = null, Optional filter As String = null) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetrics : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetrics (operations, resourceGroupName, name, workerPoolName, details, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-684">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-684">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-685">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-685">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-686">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-686">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-687">Name des workerpool</span><span class="sxs-lookup"><span data-stu-id="4bd48-687">Name of worker pool</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-688">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-688">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-689">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-689">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-690">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-690">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-691">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-691">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-692">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-692">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-693">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-693">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-694">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-694">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync (operations, resourceGroupName, name, workerPoolName, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-695">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-695">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-696">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-696">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-697">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-697">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-698">Name des workerpool</span><span class="sxs-lookup"><span data-stu-id="4bd48-698">Name of worker pool</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-699">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-699">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-700">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-700">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-701">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-701">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-702">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-702">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-703">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-703">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-704">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-704">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-705">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-705">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-706">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-706">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWebWorkerMetricsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWebWorkerMetricsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebWorkerMetricsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-707">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-707">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-708">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-708">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-709">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-709">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-710">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-710">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsNextAsync&gt;d__131))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-711">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-711">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-712">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-712">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-713">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-713">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-714">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-714">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-715">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="4bd48-715">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsages">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListWebWorkerUsages (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListWebWorkerUsages(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsages(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebWorkerUsages (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String) As IPage(Of Usage)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsages : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsages (operations, resourceGroupName, name, workerPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-716">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-716">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-717">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-717">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-718">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-718">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-719">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-719">Name of the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-720">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-720">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-721">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-721">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-722">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-722">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-723">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-723">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-724">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-724">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-725">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-725">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-726">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-726">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-727">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-727">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-728">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-728">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListWebWorkerUsagesNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt; ListWebWorkerUsagesNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebWorkerUsagesNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of Usage)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-729">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-729">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-730">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-730">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-731">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-731">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-732">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-732">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesNextAsync&gt;d__135))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-733">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-733">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-734">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-734">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-735">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-735">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-736">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-736">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-737">Abrufen von nutzungsmetriken für einen workerpool des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-737">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWorkerPoolInstanceMetricDefinitions (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWorkerPoolInstanceMetricDefinitions(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitions(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPoolInstanceMetricDefinitions (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String, instance As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitions : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitions (operations, resourceGroupName, name, workerPoolName, instance)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-738">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-738">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-739">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-739">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-740">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-740">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-741">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-741">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-742">Der Name der Instanz in die workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-742">Name of the instance in the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-743">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-743">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-744">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-744">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-745">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-745">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-746">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-746">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-747">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-747">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-748">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-748">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-749">Der Name der Instanz in die workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-749">Name of the instance in the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-750">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-750">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-751">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-751">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-752">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-752">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWorkerPoolInstanceMetricDefinitionsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListWorkerPoolInstanceMetricDefinitionsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPoolInstanceMetricDefinitionsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-753">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-753">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-754">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-754">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-755">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-755">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-756">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-756">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsNextAsync&gt;d__125))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-757">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-757">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-758">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-758">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-759">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-759">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-760">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-760">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-761">Abrufen von metrikdefinitionen für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-761">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWorkerPoolInstanceMetrics (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, Nullable&lt;bool&gt; details = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWorkerPoolInstanceMetrics(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Nullable`1&lt;bool&gt; details, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetrics(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPoolInstanceMetrics (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String, instance As String, Optional details As Nullable(Of Boolean) = null, Optional filter As String = null) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetrics : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetrics (operations, resourceGroupName, name, workerPoolName, instance, details, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-762">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-762">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-763">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-763">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-764">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-764">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-765">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-765">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-766">Der Name der Instanz in die workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-766">Name of the instance in the worker pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-767">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-767">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-768">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-768">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-769">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-769">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-770">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-770">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-771">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-771">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-772">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-772">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-773">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-773">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync (operations, resourceGroupName, name, workerPoolName, instance, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-774">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-774">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-775">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-775">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-776">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-776">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-777">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-777">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="4bd48-778">Der Name der Instanz in die workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-778">Name of the instance in the worker pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="4bd48-779">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-779">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="4bd48-780">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="4bd48-780">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4bd48-781">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="4bd48-781">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="4bd48-782">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="4bd48-782">Filter conforms to odata syntax.</span></span> <span data-ttu-id="4bd48-783">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="4bd48-783">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-784">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-784">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-785">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-785">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-786">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-786">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWorkerPoolInstanceMetricsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListWorkerPoolInstanceMetricsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPoolInstanceMetricsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-787">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-787">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-788">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-788">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-789">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-789">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-790">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-790">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsNextAsync&gt;d__127))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-791">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-791">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-792">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-792">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-793">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-793">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-794">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-794">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-795">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-795">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPools">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListWorkerPools (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListWorkerPools(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPools(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPools (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of WorkerPoolResource)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPools : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPools (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-796">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-796">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-797">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-797">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-798">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-798">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-799">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-799">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-800">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-800">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListWorkerPoolsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListWorkerPoolsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-801">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-801">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-802">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-802">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-803">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-803">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-804">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-804">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-805">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-805">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-806">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-806">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListWorkerPoolSkus (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListWorkerPoolSkus(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkus(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPoolSkus (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String) As IPage(Of SkuInfo)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkus : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkus (operations, resourceGroupName, name, workerPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-807">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-807">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-808">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-808">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-809">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-809">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-810">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-810">Name of the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-811">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-811">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-812">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-812">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-813">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-813">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-814">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-814">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-815">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-815">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-816">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-816">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-817">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-817">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-818">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-818">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-819">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-819">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListWorkerPoolSkusNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt; ListWorkerPoolSkusNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPoolSkusNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of SkuInfo)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-820">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-820">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-821">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-821">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-822">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-822">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-823">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-823">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusNextAsync&gt;d__133))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-824">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-824">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-825">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-825">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-826">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-826">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-827">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-827">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-828">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-828">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListWorkerPoolsNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; ListWorkerPoolsNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWorkerPoolsNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of WorkerPoolResource)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-829">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-829">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-830">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-830">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-831">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-831">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-832">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-832">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListWorkerPoolsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; ListWorkerPoolsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsNextAsync&gt;d__123))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-833">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-833">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-834">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-834">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-835">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-835">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-836">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-836">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-837">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="4bd48-837">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public static void Reboot (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Reboot(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Reboot(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Reboot (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Reboot : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Reboot (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-838">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-838">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-839">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-839">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-840">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-840">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-841">Alle Computer in einer App Service-Umgebung neu.</span><span class="sxs-lookup"><span data-stu-id="4bd48-841">Reboot all machines in an App Service Environment.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="4bd48-842">Alle Computer in einer App Service-Umgebung neu.</span><span class="sxs-lookup"><span data-stu-id="4bd48-842">Reboot all machines in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.RebootAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.RebootAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;RebootAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-843">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-843">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-844">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-844">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-845">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-845">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-846">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-846">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-847">Alle Computer in einer App Service-Umgebung neu.</span><span class="sxs-lookup"><span data-stu-id="4bd48-847">Reboot all machines in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-848">Alle Computer in einer App Service-Umgebung neu.</span><span class="sxs-lookup"><span data-stu-id="4bd48-848">Reboot all machines in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; Resume (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; Resume(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Resume(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resume (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Resume (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-849">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-849">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-850">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-850">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-851">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-851">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-852">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-852">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-853">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-853">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ResumeAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ResumeAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-854">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-854">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-855">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-855">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-856">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-856">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-857">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-857">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-858">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-858">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-859">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-859">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; ResumeNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; ResumeNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ResumeNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResumeNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member ResumeNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ResumeNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-860">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-860">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-861">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-861">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-862">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-862">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-863">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-863">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ResumeNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ResumeNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeNextAsync&gt;d__113))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-864">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-864">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-865">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-865">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-866">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-866">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-867">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-867">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-868">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-868">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; Suspend (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; Suspend(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Suspend(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Suspend (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member Suspend : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Suspend (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-869">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-869">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-870">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-870">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-871">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-871">Name of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-872">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-872">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-873">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-873">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; SuspendAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; SuspendAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.SuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-874">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-874">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-875">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-875">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-876">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-876">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-877">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-877">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-878">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-878">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-879">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-879">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; SuspendNext (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; SuspendNext(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.SuspendNext(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SuspendNext (operations As IAppServiceEnvironmentsOperations, nextPageLink As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member SuspendNext : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.SuspendNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-880">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-880">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-881">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-881">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-882">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-882">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-883">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-883">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; SuspendNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; SuspendNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendNextAsync&gt;d__119))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-884">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-884">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4bd48-885">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4bd48-885">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-886">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-886">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-887">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-887">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-888">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-888">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource Update (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource hostingEnvironmentEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource Update(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource hostingEnvironmentEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Update(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, hostingEnvironmentEnvelope As AppServiceEnvironmentPatchResource) As AppServiceEnvironmentResource" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.Update (operations, resourceGroupName, name, hostingEnvironmentEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-889">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-889">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-890">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-890">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-891">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-891">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="4bd48-892">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-892">Configuration details of the App Service Environment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-893">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-893">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-894">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-894">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; UpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt; UpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-895">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-895">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-896">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-896">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-897">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-897">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="4bd48-898">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-898">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-899">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-899">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-900">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-900">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-901">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-901">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMultiRolePool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource UpdateMultiRolePool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource UpdateMultiRolePool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateMultiRolePool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateMultiRolePool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, multiRolePoolEnvelope As WorkerPoolResource) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member UpdateMultiRolePool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateMultiRolePool (operations, resourceGroupName, name, multiRolePoolEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-902">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-902">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-903">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-903">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-904">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-904">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="4bd48-905">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-905">Properties of the multi-role pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-906">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-906">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-907">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-907">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; UpdateMultiRolePoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; UpdateMultiRolePoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateMultiRolePoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateMultiRolePoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;UpdateMultiRolePoolAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-908">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-908">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-909">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-909">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-910">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-910">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="4bd48-911">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-911">Properties of the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-912">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-912">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-913">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-913">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-914">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="4bd48-914">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateWorkerPool">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource UpdateWorkerPool (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource UpdateWorkerPool(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateWorkerPool(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateWorkerPool (operations As IAppServiceEnvironmentsOperations, resourceGroupName As String, name As String, workerPoolName As String, workerPoolEnvelope As WorkerPoolResource) As WorkerPoolResource" />
      <MemberSignature Language="F#" Value="static member UpdateWorkerPool : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateWorkerPool (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-915">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-915">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-916">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-916">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-917">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-917">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-918">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-918">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="4bd48-919">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-919">Properties of the worker pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-920">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-920">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-921">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-921">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; UpdateWorkerPoolAsync (this Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt; UpdateWorkerPoolAsync(class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateWorkerPoolAsync(Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateWorkerPoolAsync : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions.UpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceEnvironmentsOperationsExtensions/&lt;UpdateWorkerPoolAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4bd48-922">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4bd48-922">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4bd48-923">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="4bd48-923">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4bd48-924">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="4bd48-924">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="4bd48-925">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-925">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="4bd48-926">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="4bd48-926">Properties of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4bd48-927">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4bd48-927">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4bd48-928">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-928">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4bd48-929">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="4bd48-929">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>