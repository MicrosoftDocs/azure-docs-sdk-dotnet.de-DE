<Type Name="DeploymentsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeploymentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeploymentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeploymentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeploymentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c6a7-101">Erweiterungsmethoden für DeploymentsOperations.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-101">Extension methods for DeploymentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-103">The name of the resource group.</span></span> <span data-ttu-id="9c6a7-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-104">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-105">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-105">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c6a7-106">Zusätzliche Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-106">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-108">Erstellen Sie eine benannte vorlagenbereitstellung mithilfe einer Vorlage.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-108">Create a named template deployment using a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-110">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-110">The name of the resource group.</span></span> <span data-ttu-id="9c6a7-111">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-111">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-112">Der Name der Bereitstellung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-112">The name of the deployment to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-114">Löschen Sie Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-114">Delete deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CancelAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CancelAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;CancelAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-116">The name of the resource group.</span></span> <span data-ttu-id="9c6a7-117">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-117">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-118">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-118">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-120">Abbrechen einer derzeit ausgeführten vorlagenbereitstellung.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-120">Cancel a currently running template deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-122">Der Name der Ressourcengruppe, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-122">The name of the resource group to check.</span></span> <span data-ttu-id="9c6a7-123">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-123">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-124">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-124">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-126">Überprüft, ob die Bereitstellung vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-126">Checks whether deployment exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-128">The name of the resource group.</span></span> <span data-ttu-id="9c6a7-129">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-129">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-130">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-130">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c6a7-131">Zusätzliche Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-131">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-133">Erstellen Sie eine benannte vorlagenbereitstellung mithilfe einer Vorlage.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-133">Create a named template deployment using a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-135">The name of the resource group.</span></span> <span data-ttu-id="9c6a7-136">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-136">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-137">Der Name der Bereitstellung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-137">The name of the deployment to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-139">Löschen Sie Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-139">Delete deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-141">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-141">The name of the resource group.</span></span> <span data-ttu-id="9c6a7-142">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-142">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-143">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-143">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-145">Exportiert eine Bereitstellungsvorlage an.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-145">Exports a deployment template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.GetAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-147">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-147">The name of the resource group to get.</span></span> <span data-ttu-id="9c6a7-148">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-148">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-149">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-149">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-151">Abrufen einer Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-151">Get a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-153">Der Name der Ressourcengruppe, nach denen gefiltert werden soll.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-153">The name of the resource group to filter by.</span></span> <span data-ttu-id="9c6a7-154">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-154">The name is case insensitive.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9c6a7-155">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-155">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-157">Ruft eine Liste der Bereitstellungen.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-157">Get a list of deployments.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ListNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-158">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c6a7-159">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-159">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-161">Ruft eine Liste der Bereitstellungen.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-161">Get a list of deployments.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt; ValidateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt; ValidateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ValidateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ValidateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ValidateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c6a7-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c6a7-163">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-163">The name of the resource group.</span></span> <span data-ttu-id="9c6a7-164">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-164">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="9c6a7-165">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-165">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c6a7-166">Zu überprüfende Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9c6a7-166">Deployment to validate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c6a7-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c6a7-168">Überprüfen einer Bereitstellungsvorlage an.</span><span class="sxs-lookup"><span data-stu-id="9c6a7-168">Validate a deployment template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>