<Type Name="ContainerServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerServicesOperationsExtensions = class" />
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
            <span data-ttu-id="87930-101">Erweiterungsmethoden für ContainerServicesOperations.</span><span class="sxs-lookup"><span data-stu-id="87930-101">Extension methods for ContainerServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String, parameters As ContainerService) As ContainerService" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, containerServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-103">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-104">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-104">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87930-105">Um das Erstellen oder Aktualisieren eines Container-Dienstvorgangs angegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="87930-105">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-106">Erstellt oder aktualisiert einen containerdienst.</span><span class="sxs-lookup"><span data-stu-id="87930-106">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-107">Erstellt oder aktualisiert einen containerdienst mit der angegebenen Konfiguration von Orchestrator, Master und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-107">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-109">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-110">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-110">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87930-111">Um das Erstellen oder Aktualisieren eines Container-Dienstvorgangs angegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="87930-111">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-113">Erstellt oder aktualisiert einen containerdienst.</span><span class="sxs-lookup"><span data-stu-id="87930-113">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-114">Erstellt oder aktualisiert einen containerdienst mit der angegebenen Konfiguration von Orchestrator, Master und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-114">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDelete (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-116">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-117">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-117">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-118">Löscht den angegebenen Container-Dienst.</span><span class="sxs-lookup"><span data-stu-id="87930-118">Deletes the specified container service.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="87930-119">Löscht den angegebenen Container-Dienst in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-119">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-120">Der Vorgang löscht keine anderen Ressourcen, die als Teil des Erstellens eines Containers Diensts Speicherkonten, virtuelle Computer, einschließlich erstellt und Verfügbarkeitsgruppen.</span><span class="sxs-lookup"><span data-stu-id="87930-120">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="87930-121">Alle anderen Ressourcen erstellt, mit dem containerdienst sind Teil der gleichen Ressourcengruppe und können einzeln gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="87930-121">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-123">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-124">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-124">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-126">Löscht den angegebenen Container-Dienst.</span><span class="sxs-lookup"><span data-stu-id="87930-126">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-127">Löscht den angegebenen Container-Dienst in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-127">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-128">Der Vorgang löscht keine anderen Ressourcen, die als Teil des Erstellens eines Containers Diensts Speicherkonten, virtuelle Computer, einschließlich erstellt und Verfügbarkeitsgruppen.</span><span class="sxs-lookup"><span data-stu-id="87930-128">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="87930-129">Alle anderen Ressourcen erstellt, mit dem containerdienst sind Teil der gleichen Ressourcengruppe und können einzeln gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="87930-129">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService CreateOrUpdate (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService CreateOrUpdate(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String, parameters As ContainerService) As ContainerService" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, containerServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-131">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-132">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-132">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87930-133">Um das Erstellen oder Aktualisieren eines Container-Dienstvorgangs angegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="87930-133">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-134">Erstellt oder aktualisiert einen containerdienst.</span><span class="sxs-lookup"><span data-stu-id="87930-134">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-135">Erstellt oder aktualisiert einen containerdienst mit der angegebenen Konfiguration von Orchestrator, Master und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-135">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-137">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-137">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-138">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-138">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87930-139">Um das Erstellen oder Aktualisieren eines Container-Dienstvorgangs angegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="87930-139">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-141">Erstellt oder aktualisiert einen containerdienst.</span><span class="sxs-lookup"><span data-stu-id="87930-141">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-142">Erstellt oder aktualisiert einen containerdienst mit der angegebenen Konfiguration von Orchestrator, Master und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-142">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Delete (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-144">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-144">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-145">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-145">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-146">Löscht den angegebenen Container-Dienst.</span><span class="sxs-lookup"><span data-stu-id="87930-146">Deletes the specified container service.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="87930-147">Löscht den angegebenen Container-Dienst in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-147">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-148">Der Vorgang löscht keine anderen Ressourcen, die als Teil des Erstellens eines Containers Diensts Speicherkonten, virtuelle Computer, einschließlich erstellt und Verfügbarkeitsgruppen.</span><span class="sxs-lookup"><span data-stu-id="87930-148">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="87930-149">Alle anderen Ressourcen erstellt, mit dem containerdienst sind Teil der gleichen Ressourcengruppe und können einzeln gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="87930-149">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-151">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-152">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-152">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-154">Löscht den angegebenen Container-Dienst.</span><span class="sxs-lookup"><span data-stu-id="87930-154">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-155">Löscht den angegebenen Container-Dienst in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-155">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-156">Der Vorgang löscht keine anderen Ressourcen, die als Teil des Erstellens eines Containers Diensts Speicherkonten, virtuelle Computer, einschließlich erstellt und Verfügbarkeitsgruppen.</span><span class="sxs-lookup"><span data-stu-id="87930-156">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="87930-157">Alle anderen Ressourcen erstellt, mit dem containerdienst sind Teil der gleichen Ressourcengruppe und können einzeln gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="87930-157">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService Get (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService Get(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String) As ContainerService" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Get (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-159">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-160">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-160">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-161">Ruft die Eigenschaften des Diensts angegebenen Container ab.</span><span class="sxs-lookup"><span data-stu-id="87930-161">Gets the properties of the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-162">Ruft die Eigenschaften des Diensts angegebenen Container in der angegebenen Abonnement und die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="87930-162">Gets the properties of the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-163">Der Vorgang gibt die Eigenschaften, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und -Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-163">The operation returns the properties including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; GetAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; GetAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.GetAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-165">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-165">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="87930-166">Der Name des Diensts Container in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-166">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-168">Ruft die Eigenschaften des Diensts angegebenen Container ab.</span><span class="sxs-lookup"><span data-stu-id="87930-168">Gets the properties of the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-169">Ruft die Eigenschaften des Diensts angegebenen Container in der angegebenen Abonnement und die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="87930-169">Gets the properties of the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-170">Der Vorgang gibt die Eigenschaften, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und -Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-170">The operation returns the properties including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; List (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; List(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IContainerServicesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IContainerServicesOperations) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IContainerServicesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-171">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-172">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-172">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-173">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-173">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="87930-174">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-174">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-175">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-177">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-177">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-178">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-178">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="87930-179">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-179">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroup (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroup(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IContainerServicesOperations, resourceGroupName As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-181">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-181">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-182">Ruft eine Liste der Container-Dienste in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-182">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-183">Ruft eine Liste der Container-Dienste in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-183">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-184">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-184">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87930-186">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-186">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-188">Ruft eine Liste der Container-Dienste in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-188">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-189">Ruft eine Liste der Container-Dienste in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-189">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-190">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-190">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IContainerServicesOperations, nextPageLink As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87930-192">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87930-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-193">Ruft eine Liste der Container-Dienste in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-193">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-194">Ruft eine Liste der Container-Dienste in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-194">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-195">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-195">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-196">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87930-197">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87930-197">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-199">Ruft eine Liste der Container-Dienste in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="87930-199">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-200">Ruft eine Liste der Container-Dienste in der angegebenen Gruppe von Abonnement- und Ressourcenstatus.</span><span class="sxs-lookup"><span data-stu-id="87930-200">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="87930-201">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-201">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListNext (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListNext(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IContainerServicesOperations, nextPageLink As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87930-203">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87930-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-204">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-204">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-205">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-205">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="87930-206">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-206">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87930-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87930-207">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87930-208">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87930-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87930-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87930-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87930-210">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-210">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="87930-211">Ruft eine Liste der Container-Dienste in das angegebene Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="87930-211">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="87930-212">Der Vorgang gibt die Eigenschaften der einzelnen Container-Dienste, einschließlich Status, Orchestrator, Anzahl der Master-Shapes und Agents und FQDNs der Master-Shapes und Agents.</span><span class="sxs-lookup"><span data-stu-id="87930-212">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>