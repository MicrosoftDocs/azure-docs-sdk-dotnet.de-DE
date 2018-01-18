<Type Name="PolicyAssignmentsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PolicyAssignmentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PolicyAssignmentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PolicyAssignmentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PolicyAssignmentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0f375-101">Erweiterungsmethoden für PolicyAssignmentsOperations.</span><span class="sxs-lookup"><span data-stu-id="0f375-101">Extension methods for PolicyAssignmentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Create (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Create(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Create(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IPolicyAssignmentsOperations, scope As String, policyAssignmentName As String, parameters As PolicyAssignment) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Create (operations, scope, policyAssignmentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-102">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="0f375-103">Der Bereich der für richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-103">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="0f375-104">Der Name der richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-104">The name of the policy assignment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0f375-105">Parameter für die Zuweisung der Konfigurationsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="0f375-105">Parameters for the policy assignment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-106">Erstellt eine Zuweisung der Konfigurationsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="0f375-106">Creates a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-107">Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt.</span><span class="sxs-lookup"><span data-stu-id="0f375-107">Policy assignments are inherited by child resources.</span></span> <span data-ttu-id="0f375-108">Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="0f375-108">For example, when you apply a policy to a resource group that policy is assigned to all resources in the group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateAsync (operations, scope, policyAssignmentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-109">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="0f375-110">Der Bereich der für richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-110">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="0f375-111">Der Name der richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-111">The name of the policy assignment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0f375-112">Parameter für die Zuweisung der Konfigurationsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="0f375-112">Parameters for the policy assignment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-114">Erstellt eine Zuweisung der Konfigurationsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="0f375-114">Creates a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-115">Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt.</span><span class="sxs-lookup"><span data-stu-id="0f375-115">Policy assignments are inherited by child resources.</span></span> <span data-ttu-id="0f375-116">Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="0f375-116">For example, when you apply a policy to a resource group that policy is assigned to all resources in the group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment CreateById (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment CreateById(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateById(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateById (operations As IPolicyAssignmentsOperations, policyAssignmentId As String, parameters As PolicyAssignment) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member CreateById : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateById (operations, policyAssignmentId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-117">The operations group for this extension method.</span></span>
            </param>
        <param name="policyAssignmentId">
            <span data-ttu-id="0f375-118">Die ID der für richtlinienzuweisung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="0f375-118">The ID of the policy assignment to create.</span></span> <span data-ttu-id="0f375-119">Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".</span><span class="sxs-lookup"><span data-stu-id="0f375-119">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0f375-120">Parameter für die Zuweisung der Konfigurationsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="0f375-120">Parameters for policy assignment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-121">Erstellt eine richtlinienzuweisung anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="0f375-121">Creates a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-122">Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt.</span><span class="sxs-lookup"><span data-stu-id="0f375-122">Policy assignments are inherited by child resources.</span></span> <span data-ttu-id="0f375-123">Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="0f375-123">For example, when you apply a policy to a resource group that policy is assigned to all resources in the group.</span></span> <span data-ttu-id="0f375-124">Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="0f375-124">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateByIdAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; CreateByIdAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateByIdAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateByIdAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.CreateByIdAsync (operations, policyAssignmentId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;CreateByIdAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-125">The operations group for this extension method.</span></span>
            </param>
        <param name="policyAssignmentId">
            <span data-ttu-id="0f375-126">Die ID der für richtlinienzuweisung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="0f375-126">The ID of the policy assignment to create.</span></span> <span data-ttu-id="0f375-127">Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".</span><span class="sxs-lookup"><span data-stu-id="0f375-127">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0f375-128">Parameter für die Zuweisung der Konfigurationsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="0f375-128">Parameters for policy assignment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-130">Erstellt eine richtlinienzuweisung anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="0f375-130">Creates a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-131">Richtlinienzuweisungen werden von untergeordneten Ressourcen geerbt.</span><span class="sxs-lookup"><span data-stu-id="0f375-131">Policy assignments are inherited by child resources.</span></span> <span data-ttu-id="0f375-132">Beispielsweise, wenn Sie eine Richtlinie in einer Ressourcengruppe anwenden, die Richtlinie auf alle Ressourcen in der Gruppe zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="0f375-132">For example, when you apply a policy to a resource group that policy is assigned to all resources in the group.</span></span> <span data-ttu-id="0f375-133">Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="0f375-133">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Delete (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Delete(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IPolicyAssignmentsOperations, scope As String, policyAssignmentName As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Delete (operations, scope, policyAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-134">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="0f375-135">Der Bereich der für richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-135">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="0f375-136">Der Name der richtlinienzuweisung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0f375-136">The name of the policy assignment to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-137">Löscht eine richtlinienzuweisung an.</span><span class="sxs-lookup"><span data-stu-id="0f375-137">Deletes a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteAsync (operations, scope, policyAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-138">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="0f375-139">Der Bereich der für richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-139">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="0f375-140">Der Name der richtlinienzuweisung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0f375-140">The name of the policy assignment to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-142">Löscht eine richtlinienzuweisung an.</span><span class="sxs-lookup"><span data-stu-id="0f375-142">Deletes a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment DeleteById (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment DeleteById(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteById(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteById (operations As IPolicyAssignmentsOperations, policyAssignmentId As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member DeleteById : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteById (operations, policyAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-143">The operations group for this extension method.</span></span>
            </param>
        <param name="policyAssignmentId">
            <span data-ttu-id="0f375-144">Die ID der für richtlinienzuweisung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0f375-144">The ID of the policy assignment to delete.</span></span> <span data-ttu-id="0f375-145">Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".</span><span class="sxs-lookup"><span data-stu-id="0f375-145">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-146">Löscht eine richtlinienzuweisung anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="0f375-146">Deletes a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-147">Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="0f375-147">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteByIdAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; DeleteByIdAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteByIdAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteByIdAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.DeleteByIdAsync (operations, policyAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;DeleteByIdAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-148">The operations group for this extension method.</span></span>
            </param>
        <param name="policyAssignmentId">
            <span data-ttu-id="0f375-149">Die ID der für richtlinienzuweisung zu löschen.</span><span class="sxs-lookup"><span data-stu-id="0f375-149">The ID of the policy assignment to delete.</span></span> <span data-ttu-id="0f375-150">Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".</span><span class="sxs-lookup"><span data-stu-id="0f375-150">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-152">Löscht eine richtlinienzuweisung anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="0f375-152">Deletes a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-153">Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="0f375-153">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Get (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment Get(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPolicyAssignmentsOperations, scope As String, policyAssignmentName As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.Get (operations, scope, policyAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-154">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="0f375-155">Der Bereich der für richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-155">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="0f375-156">Der Name der richtlinienzuweisung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="0f375-156">The name of the policy assignment to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-157">Ruft eine richtlinienzuweisung ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-157">Gets a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string scope, string policyAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetAsync (operations, scope, policyAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-158">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="0f375-159">Der Bereich der für richtlinienzuweisung.</span><span class="sxs-lookup"><span data-stu-id="0f375-159">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="0f375-160">Der Name der richtlinienzuweisung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="0f375-160">The name of the policy assignment to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-162">Ruft eine richtlinienzuweisung ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-162">Gets a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment GetById (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment GetById(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetById(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetById (operations As IPolicyAssignmentsOperations, policyAssignmentId As String) As PolicyAssignment" />
      <MemberSignature Language="F#" Value="static member GetById : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetById (operations, policyAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-163">The operations group for this extension method.</span></span>
            </param>
        <param name="policyAssignmentId">
            <span data-ttu-id="0f375-164">Die ID der richtlinienzuweisung abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0f375-164">The ID of the policy assignment to get.</span></span> <span data-ttu-id="0f375-165">Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".</span><span class="sxs-lookup"><span data-stu-id="0f375-165">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-166">Ruft eine richtlinienzuweisung anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="0f375-166">Gets a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-167">Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="0f375-167">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetByIdAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; GetByIdAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string policyAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetByIdAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByIdAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.GetByIdAsync (operations, policyAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;GetByIdAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-168">The operations group for this extension method.</span></span>
            </param>
        <param name="policyAssignmentId">
            <span data-ttu-id="0f375-169">Die ID der richtlinienzuweisung abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0f375-169">The ID of the policy assignment to get.</span></span> <span data-ttu-id="0f375-170">Verwenden Sie das Format "/ {scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}".</span><span class="sxs-lookup"><span data-stu-id="0f375-170">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-172">Ruft eine richtlinienzuweisung anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="0f375-172">Gets a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="0f375-173">Verwenden Sie bei der Angabe eines Bereichs für die speicherzuweisung "/ Subscriptions / {Abonnement-Id} /" für "/ Subscriptions / {Abonnement-Id} / ResourceGroups / {Resource-Group-Name}" für Ressourcengruppen, Abonnements und "/ subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="0f375-173">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; List (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; List(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPolicyAssignmentsOperations, Optional odataQuery As ODataQuery(Of PolicyAssignment) = null) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-174">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="0f375-175">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="0f375-175">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-176">Ruft die richtlinienzuweisungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-176">Gets all the policy assignments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-177">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="0f375-178">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="0f375-178">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-180">Ruft die richtlinienzuweisungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-180">Gets all the policy assignments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResource">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResource (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResource(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResource(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResource (operations As IPolicyAssignmentsOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, Optional odataQuery As ODataQuery(Of PolicyAssignment) = null) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResource : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResource (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f375-182">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0f375-182">The name of the resource group containing the resource.</span></span> <span data-ttu-id="0f375-183">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="0f375-183">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0f375-184">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="0f375-184">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="0f375-185">Die übergeordnete Ressourcenpfad.</span><span class="sxs-lookup"><span data-stu-id="0f375-185">The parent resource path.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="0f375-186">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="0f375-186">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="0f375-187">Der Name der Ressource mit zugewiesenen Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="0f375-187">The name of the resource with policy assignments.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="0f375-188">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="0f375-188">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-189">Ruft die richtlinienzuweisungen für eine Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-189">Gets policy assignments for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f375-191">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="0f375-191">The name of the resource group containing the resource.</span></span> <span data-ttu-id="0f375-192">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="0f375-192">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0f375-193">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="0f375-193">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="0f375-194">Die übergeordnete Ressourcenpfad.</span><span class="sxs-lookup"><span data-stu-id="0f375-194">The parent resource path.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="0f375-195">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="0f375-195">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="0f375-196">Der Name der Ressource mit zugewiesenen Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="0f375-196">The name of the resource with policy assignments.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="0f375-197">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="0f375-197">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-199">Ruft die richtlinienzuweisungen für eine Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-199">Gets policy assignments for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroup (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroup(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroup(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroup (operations As IPolicyAssignmentsOperations, resourceGroupName As String, Optional filter As String = null) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroup : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroup (operations, resourceGroupName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f375-201">Der Name der Ressourcengruppe, die richtlinienzuweisungen enthält.</span><span class="sxs-lookup"><span data-stu-id="0f375-201">The name of the resource group that contains policy assignments.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="0f375-202">Der Filter auf die Operation angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0f375-202">The filter to apply on the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-203">Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-203">Gets policy assignments for the resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string resourceGroupName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupAsync (operations, resourceGroupName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0f375-205">Der Name der Ressourcengruppe, die richtlinienzuweisungen enthält.</span><span class="sxs-lookup"><span data-stu-id="0f375-205">The name of the resource group that contains policy assignments.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="0f375-206">Der Filter auf die Operation angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0f375-206">The filter to apply on the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-208">Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-208">Gets policy assignments for the resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroupNext (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceGroupNext(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNext(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroupNext (operations As IPolicyAssignmentsOperations, nextPageLink As String) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupNext : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-209">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0f375-210">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0f375-210">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-211">Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-211">Gets policy assignments for the resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceGroupNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceGroupNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-212">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0f375-213">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0f375-213">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-214">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-215">Ruft die richtlinienzuweisungen für die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-215">Gets policy assignments for the resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceNext (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListForResourceNext(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNext(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceNext (operations As IPolicyAssignmentsOperations, nextPageLink As String) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListForResourceNext : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-216">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0f375-217">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0f375-217">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-218">Ruft die richtlinienzuweisungen für eine Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-218">Gets policy assignments for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListForResourceNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListForResourceNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListForResourceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListForResourceNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-219">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0f375-220">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0f375-220">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-222">Ruft die richtlinienzuweisungen für eine Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-222">Gets policy assignments for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPolicyAssignmentsOperations, nextPageLink As String) As IPage(Of PolicyAssignment)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-223">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0f375-224">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0f375-224">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-225">Ruft die richtlinienzuweisungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-225">Gets all the policy assignments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyAssignmentsOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0f375-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0f375-226">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0f375-227">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0f375-227">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0f375-228">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0f375-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0f375-229">Ruft die richtlinienzuweisungen für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="0f375-229">Gets all the policy assignments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>