<Type Name="AppServiceEnvironmentsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceEnvironmentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironmentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3a5c5-101">Erweiterungsmethoden für AppServiceEnvironmentsOperations.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-101">Extension methods for AppServiceEnvironmentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-104">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-104">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="3a5c5-105">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-105">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-107">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-107">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-108">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-108">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateMultiRolePoolAsync&gt;d__38))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-110">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-111">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-111">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="3a5c5-112">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-112">Properties of the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-114">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-114">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-115">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-115">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateWorkerPoolAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-117">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-117">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-118">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-118">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3a5c5-119">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-119">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="3a5c5-120">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-120">Properties of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-122">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-122">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-123">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-123">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-125">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-126">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-126">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="3a5c5-127">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den Löschvorgang zu erzwingen, auch wenn die App Service-Umgebung Ressourcen enthält.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-127">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="3a5c5-128">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-128">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-130">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-130">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-131">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-131">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-133">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-134">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-134">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-136">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-136">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-137">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-137">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeNextAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-138">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-139">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-139">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-141">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-141">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-142">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-142">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-144">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-145">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-145">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-147">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-147">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-148">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-148">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendNextAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-149">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-150">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-152">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-152">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-153">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-153">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-155">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-155">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-156">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-156">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="3a5c5-157">Konfigurationsdetails des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-157">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-159">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-159">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-160">Erstellen oder Aktualisieren einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-160">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateMultiRolePoolAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-162">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-162">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-163">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-163">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="3a5c5-164">Eigenschaften des Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-164">Properties of the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-166">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-166">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-167">Erstellen Sie oder aktualisieren Sie einen Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-167">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateWorkerPoolAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-169">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-169">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-170">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-170">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3a5c5-171">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-171">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="3a5c5-172">Eigenschaften des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-172">Properties of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-174">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-174">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-175">Erstellen Sie oder aktualisieren Sie einen workerpool.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-175">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-177">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-177">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-178">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-178">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="3a5c5-179">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den Löschvorgang zu erzwingen, auch wenn die App Service-Umgebung Ressourcen enthält.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-179">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="3a5c5-180">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-180">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-182">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-182">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-183">Löschen Sie eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-183">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-185">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-185">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-186">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-186">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-188">Rufen Sie die Eigenschaften der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-188">Get the properties of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-189">Rufen Sie die Eigenschaften der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-189">Get the properties of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDiagnosticsItemAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt; GetDiagnosticsItemAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt; GetDiagnosticsItemAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDiagnosticsItemAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync (operations, resourceGroupName, name, diagnosticsName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetDiagnosticsItemAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="diagnosticsName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-191">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-191">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-192">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-192">Name of the App Service Environment.</span></span>
            </param>
        <param name="diagnosticsName">
            <span data-ttu-id="3a5c5-193">Der Name des Diagnose-Elements.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-193">Name of the diagnostics item.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-195">Ruft ein Element für die Diagnose für App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-195">Get a diagnostics item for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-196">Ruft ein Element für die Diagnose für App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-196">Get a diagnostics item for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetMultiRolePoolAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-198">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-198">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-199">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-199">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-201">Rufen Sie die Eigenschaften eines Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-201">Get properties of a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-202">Rufen Sie die Eigenschaften eines Pools mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-202">Get properties of a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetWorkerPoolAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-203">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-203">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-204">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-204">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-205">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-205">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3a5c5-206">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-206">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-208">Rufen Sie die Eigenschaften eines Pools mit Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-208">Get properties of a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-209">Rufen Sie die Eigenschaften eines Pools mit Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-209">Get properties of a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-211">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-211">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-212">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-212">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-213">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-214">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-214">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-215">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-215">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansNextAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-216">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-217">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-217">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-219">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-219">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-220">Erhalten Sie alle App Service-Pläne in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-220">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-221">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-223">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-223">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-224">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-224">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-226">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-226">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-228">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-228">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-229">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-229">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-230">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-230">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-231">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-231">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-232">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-233">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-233">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-234">Ruft alle App Service-Umgebungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-234">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-235">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-236">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-236">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-237">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-237">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-239">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-239">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-240">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-240">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesNextAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-241">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-241">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-242">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-242">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-243">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-244">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-244">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-245">Abrufen der Kapazität verwendet, zur Verfügung und insgesamt Worker App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-245">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDiagnosticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt; ListDiagnosticsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt; ListDiagnosticsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDiagnosticsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListDiagnosticsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-246">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-246">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-247">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-247">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-248">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-248">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-249">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-250">Abrufen von Diagnoseinformationen für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-250">Get diagnostic information for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-251">Abrufen von Diagnoseinformationen für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-251">Get diagnostic information for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt; ListMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt; ListMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricDefinitionsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-253">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-253">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-254">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-254">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-255">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-256">Rufen Sie die globale metrikdefinitionen der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-256">Get global metric definitions of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-257">Rufen Sie die globale metrikdefinitionen der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-257">Get global metric definitions of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-258">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-258">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-259">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-259">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-260">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-260">Name of the App Service Environment.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3a5c5-261">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-261">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3a5c5-262">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-262">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3a5c5-263">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-263">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3a5c5-264">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-264">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3a5c5-265">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="3a5c5-265">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-266">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-267">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-267">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-268">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-268">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-269">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-269">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-270">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-270">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-271">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-272">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-272">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-273">Globale Metriken der App Service-Umgebung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-273">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsNextAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime = null, string endTime = null, string timeGrain = null, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime, string endTime, string timeGrain, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync (operations, resourceGroupName, name, startTime, endTime, timeGrain, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            <span data-ttu-id="3a5c5-274">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-274">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-275">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-275">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-276">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-276">Name of the App Service Environment.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="3a5c5-277">Der Anfangszeit der Metriken Abfrage.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-277">Beginning time of the metrics query.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="3a5c5-278">Beendigungszeit der Abfrage Metriken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-278">End time of the metrics query.</span></span>
            </param>
        <param name="timeGrain">
            <span data-ttu-id="3a5c5-279">Zeitgranularität der Metriken Abfrage.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-279">Time granularity of the metrics query.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3a5c5-280">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-280">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3a5c5-281">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-281">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3a5c5-282">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-282">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3a5c5-283">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-283">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3a5c5-284">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="3a5c5-284">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-285">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-286">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-286">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-287">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-287">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsNextAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-288">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-288">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-289">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-289">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-290">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-291">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-291">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-292">Abrufen von Metriken für einen Pool mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-292">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="instance">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsNextAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, Nullable&lt;bool&gt; details = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Nullable`1&lt;bool&gt; details, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync (operations, resourceGroupName, name, instance, details, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-293">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-293">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-294">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-294">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-295">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-295">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="3a5c5-296">Der Name der Instanz im Pool mit mehreren Rollen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-296">Name of the instance in the multi-role pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3a5c5-297">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-297">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3a5c5-298">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-298">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-299">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-300">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-300">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-301">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-301">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsNextAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-302">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-302">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-303">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-303">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-304">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-304">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-305">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-305">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-306">Abrufen von Metriken für eine bestimmte Instanz eines Pools mit mehreren Rollen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-306">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-307">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-307">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-308">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-308">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-309">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-309">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-310">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-311">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-311">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-312">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-312">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-313">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-313">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-314">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-314">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-315">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-315">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-316">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-317">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-317">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-318">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-318">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusNextAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-319">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-319">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-320">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-320">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-321">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-322">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-322">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-323">Verfügbare SKUs für Skalierung einen Pool mit mehreren Rollen abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-323">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsNextAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-324">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-324">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-325">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-325">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-326">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-327">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-327">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-328">Rufen Sie aller multifunktionalen Pools an ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-328">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesNextAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListNextAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-329">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-329">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-330">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-330">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-331">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-331">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-332">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-332">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-333">Ruft alle App Service-Umgebungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-333">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListOperationsAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-334">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-334">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-335">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-335">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-336">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-336">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-337">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-337">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-338">Listen Sie alle derzeit ausgeführten Vorgänge für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-338">List all currently running operations on the App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-339">Listen Sie alle derzeit ausgeführten Vorgänge für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-339">List all currently running operations on the App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, name, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-340">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-340">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-341">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-341">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-342">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-342">Name of the App Service Environment.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3a5c5-343">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-343">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3a5c5-344">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-344">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3a5c5-345">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="3a5c5-345">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-346">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-346">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-347">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-347">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-348">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-348">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesNextAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-349">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-349">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-350">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-350">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-351">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-351">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-352">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-352">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-353">Rufen Sie globale nutzungsmetriken der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-353">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVipsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt; ListVipsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt; ListVipsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVipsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListVipsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-354">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-354">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-355">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-355">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-356">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-356">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-357">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-357">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-358">Get IP-Adressen in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-358">Get IP addresses assigned to an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-359">Get IP-Adressen in einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-359">Get IP addresses assigned to an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, propertiesToInclude, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="propertiesToInclude" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-360">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-360">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-361">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-361">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-362">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-362">Name of the App Service Environment.</span></span>
            </param>
        <param name="propertiesToInclude">
            <span data-ttu-id="3a5c5-363">Durch Trennzeichen getrennte Liste von app-Eigenschaften eingeschlossen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-363">Comma separated list of app properties to include.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-364">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-364">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-365">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-365">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-366">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-366">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-367">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-367">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-368">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-368">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-369">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-369">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-370">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-370">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-371">Erhalten Sie alle apps im App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-371">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsNextAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync (operations, resourceGroupName, name, workerPoolName, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-372">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-372">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-373">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-373">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-374">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-374">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3a5c5-375">Name des workerpool</span><span class="sxs-lookup"><span data-stu-id="3a5c5-375">Name of worker pool</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3a5c5-376">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-376">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3a5c5-377">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-377">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3a5c5-378">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-378">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3a5c5-379">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-379">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3a5c5-380">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="3a5c5-380">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-381">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-382">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="3a5c5-382">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-383">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="3a5c5-383">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsNextAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-384">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-384">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-385">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-385">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-386">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-386">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-387">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="3a5c5-387">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-388">Abrufen von Metriken für einen workerpool von einem AppServiceEnvironment (App Service-Umgebung).</span><span class="sxs-lookup"><span data-stu-id="3a5c5-388">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesNextAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="instance">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsNextAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync (operations, resourceGroupName, name, workerPoolName, instance, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
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
            <span data-ttu-id="3a5c5-389">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-389">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-390">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-390">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-391">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-391">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3a5c5-392">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-392">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="3a5c5-393">Der Name der Instanz in die workerpool.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-393">Name of the instance in the worker pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3a5c5-394">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; Instanzdetails einschließen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-394">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3a5c5-395">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-395">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3a5c5-396">Geben Sie nur Verwendungen/Metriken-im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-396">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3a5c5-397">Filter entspricht OData-Syntax.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-397">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3a5c5-398">Beispiel: $filter = (name.value Eq "Metric1" oder name.value Eq "Metric2") und StartTime-Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[Stunde | Minute | Tag] ".</span><span class="sxs-lookup"><span data-stu-id="3a5c5-398">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-399">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-399">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-400">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-400">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-401">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-401">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsNextAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-402">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-402">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-403">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-403">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-404">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-404">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-405">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-405">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-406">Abrufen von Metriken für eine bestimmte Instanz eines Pools Worker des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-406">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-407">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-407">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-408">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-408">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-409">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-409">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-410">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-410">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-411">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-411">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-412">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-412">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-413">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-413">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-414">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-414">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-415">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-415">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3a5c5-416">Der Name des Pools Worker.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-416">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-417">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-417">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-418">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-418">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-419">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-419">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusNextAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-420">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-420">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-421">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-421">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-422">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-422">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-423">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-423">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-424">Verfügbare SKUs für einen workerpool Skalierung abrufen.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-424">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsNextAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-425">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-425">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-426">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-426">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-427">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-427">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-428">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-428">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-429">Rufen Sie aller workerpools des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-429">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.RebootAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.RebootAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;RebootAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-430">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-430">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-431">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-431">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-432">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-432">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-433">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-433">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-434">Alle Computer in einer App Service-Umgebung neu.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-434">Reboot all machines in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-435">Alle Computer in einer App Service-Umgebung neu.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-435">Reboot all machines in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-436">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-436">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-437">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-437">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-438">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-438">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-439">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-439">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-440">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-440">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-441">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-441">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeNextAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-442">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-442">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-443">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-443">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-444">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-444">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-445">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-445">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-446">Fortsetzen einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-446">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-447">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-447">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3a5c5-448">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-448">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3a5c5-449">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-449">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-450">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-450">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-451">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-451">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-452">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-452">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendNextAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3a5c5-453">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-453">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3a5c5-454">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-454">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3a5c5-455">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-455">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3a5c5-456">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-456">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3a5c5-457">Anhalten einer App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3a5c5-457">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>