<Type Name="NamespacesOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NamespacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NamespacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NamespacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NamespacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="182a1-101">Erweiterungsmethoden für NamespacesOperations.</span><span class="sxs-lookup"><span data-stu-id="182a1-101">Extension methods for NamespacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDelete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-103">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-104">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-104">The namespace name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-105">Löscht einen vorhandenen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-105">Deletes an existing namespace.</span></span> <span data-ttu-id="182a1-106">Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-106">This operation also removes all associated notificationHubs under the namespace.</span></span>
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-108">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-109">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-109">The namespace name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-111">Löscht einen vorhandenen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-111">Deletes an existing namespace.</span></span> <span data-ttu-id="182a1-112">Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-112">This operation also removes all associated notificationHubs under the namespace.</span></span>
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As INamespacesOperations, parameters As CheckAvailabilityParameters) As CheckAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-113">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-114">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-114">The namespace name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-115">Überprüft die Verfügbarkeit des angegebenen Dienstnamespace über alle Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="182a1-115">Checks the availability of the given service namespace across all Azure subscriptions.</span></span> <span data-ttu-id="182a1-116">Dies ist hilfreich, da der Domänenname basierend auf den Dienstnamespace erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="182a1-116">This is useful because the domain name is created based on the service namespace name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-117">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-118">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-118">The namespace name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-120">Überprüft die Verfügbarkeit des angegebenen Dienstnamespace über alle Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="182a1-120">Checks the availability of the given service namespace across all Azure subscriptions.</span></span> <span data-ttu-id="182a1-121">Dies ist hilfreich, da der Domänenname basierend auf den Dienstnamespace erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="182a1-121">This is useful because the domain name is created based on the service namespace name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource CreateOrUpdate (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource CreateOrUpdate(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As NamespaceCreateOrUpdateParameters) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-123">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-124">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-124">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-125">Parameter, die zum Erstellen einer Ressource Namespace angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="182a1-125">Parameters supplied to create a Namespace Resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-126">Erstellungsvorgänge/Updates ein dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="182a1-126">Creates/Updates a service namespace.</span></span> <span data-ttu-id="182a1-127">Nach der Erstellung ist das ressourcenmanifest des Namespaces unveränderlich.</span><span class="sxs-lookup"><span data-stu-id="182a1-127">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="182a1-128">Dieser Vorgang ist Idempotent.</span><span class="sxs-lookup"><span data-stu-id="182a1-128">This operation is idempotent.</span></span>
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856303.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-130">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-130">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-131">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-131">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-132">Parameter, die zum Erstellen einer Ressource Namespace angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="182a1-132">Parameters supplied to create a Namespace Resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-134">Erstellungsvorgänge/Updates ein dienstnamespaces.</span><span class="sxs-lookup"><span data-stu-id="182a1-134">Creates/Updates a service namespace.</span></span> <span data-ttu-id="182a1-135">Nach der Erstellung ist das ressourcenmanifest des Namespaces unveränderlich.</span><span class="sxs-lookup"><span data-stu-id="182a1-135">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="182a1-136">Dieser Vorgang ist Idempotent.</span><span class="sxs-lookup"><span data-stu-id="182a1-136">This operation is idempotent.</span></span>
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856303.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As SharedAccessAuthorizationRuleCreateOrUpdateParameters) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-138">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-138">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-139">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-139">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-140">Aauthorization Regelname.</span><span class="sxs-lookup"><span data-stu-id="182a1-140">Aauthorization Rule Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-141">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="182a1-141">The shared access authorization rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-142">Erstellt eine Autorisierungsregel für einen namespace</span><span class="sxs-lookup"><span data-stu-id="182a1-142">Creates an authorization rule for a namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-144">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-144">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-145">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-145">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-146">Aauthorization Regelname.</span><span class="sxs-lookup"><span data-stu-id="182a1-146">Aauthorization Rule Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-147">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="182a1-147">The shared access authorization rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-149">Erstellt eine Autorisierungsregel für einen namespace</span><span class="sxs-lookup"><span data-stu-id="182a1-149">Creates an authorization rule for a namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Delete(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Delete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-151">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-152">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-152">The namespace name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-153">Löscht einen vorhandenen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-153">Deletes an existing namespace.</span></span> <span data-ttu-id="182a1-154">Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-154">This operation also removes all associated notificationHubs under the namespace.</span></span>
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-156">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-157">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-157">The namespace name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-159">Löscht einen vorhandenen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-159">Deletes an existing namespace.</span></span> <span data-ttu-id="182a1-160">Dieser Vorgang entfernt auch alle zugeordneten NotificationHubs unter dem Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-160">This operation also removes all associated notificationHubs under the namespace.</span></span>
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-162">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-162">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-163">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-163">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-164">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="182a1-164">Authorization Rule Name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-165">Löscht eine Namespace-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="182a1-165">Deletes a namespace authorization rule</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-167">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-167">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-168">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-168">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-169">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="182a1-169">Authorization Rule Name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-171">Löscht eine Namespace-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="182a1-171">Deletes a namespace authorization rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Get (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Get(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Get(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Get (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-173">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-173">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-174">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-174">The namespace name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-175">Gibt die Beschreibung für den angegebenen Namespace zurück.</span><span class="sxs-lookup"><span data-stu-id="182a1-175">Returns the description for the specified namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; GetAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; GetAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-177">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-177">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-178">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-178">The namespace name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-180">Gibt die Beschreibung für den angegebenen Namespace zurück.</span><span class="sxs-lookup"><span data-stu-id="182a1-180">Returns the description for the specified namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-182">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-182">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-183">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="182a1-183">The namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-184">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="182a1-184">Authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-185">Ruft eine Autorisierungsregel für einen Namespace nach Name ab.</span><span class="sxs-lookup"><span data-stu-id="182a1-185">Gets an authorization rule for a namespace by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-187">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-187">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-188">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="182a1-188">The namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-189">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="182a1-189">Authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-191">Ruft eine Autorisierungsregel für einen Namespace nach Name ab.</span><span class="sxs-lookup"><span data-stu-id="182a1-191">Gets an authorization rule for a namespace by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; List (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; List(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.List(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INamespacesOperations, resourceGroupName As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-193">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-193">The name of the resource group.</span></span> <span data-ttu-id="182a1-194">Wenn ResourceGroupName Wert null ist, führt die Methode alle Namespaces in Abonnement</span><span class="sxs-lookup"><span data-stu-id="182a1-194">If resourceGroupName value is null the method lists all the namespaces within subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-195">Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".</span><span class="sxs-lookup"><span data-stu-id="182a1-195">Lists the available namespaces within a resourceGroup.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAll (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAll(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAll(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INamespacesOperations) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-196">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-197">Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.</span><span class="sxs-lookup"><span data-stu-id="182a1-197">Lists all the available namespaces within the subscription irrespective of the resourceGroups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAllAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-198">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-200">Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.</span><span class="sxs-lookup"><span data-stu-id="182a1-200">Lists all the available namespaces within the subscription irrespective of the resourceGroups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAllNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAllNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-201">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="182a1-202">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="182a1-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-203">Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.</span><span class="sxs-lookup"><span data-stu-id="182a1-203">Lists all the available namespaces within the subscription irrespective of the resourceGroups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAllNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-204">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="182a1-205">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="182a1-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-207">Listet die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der ResourceGroups an.</span><span class="sxs-lookup"><span data-stu-id="182a1-207">Lists all the available namespaces within the subscription irrespective of the resourceGroups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-209">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-209">The name of the resource group.</span></span> <span data-ttu-id="182a1-210">Wenn ResourceGroupName Wert null ist, führt die Methode alle Namespaces in Abonnement</span><span class="sxs-lookup"><span data-stu-id="182a1-210">If resourceGroupName value is null the method lists all the namespaces within subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-211">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-212">Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".</span><span class="sxs-lookup"><span data-stu-id="182a1-212">Lists the available namespaces within a resourceGroup.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-213">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-214">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-214">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-215">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="182a1-215">The namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-216">Ruft die Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-216">Gets the authorization rules for a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-217">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-217">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-218">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-218">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-219">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="182a1-219">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-220">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-221">Ruft die Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-221">Gets the authorization rules for a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-222">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-222">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="182a1-223">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="182a1-223">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-224">Ruft die Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-224">Gets the authorization rules for a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-225">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="182a1-226">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="182a1-226">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-228">Ruft die Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="182a1-228">Gets the authorization rules for a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeys(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-230">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-230">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-231">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-231">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-232">Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="182a1-232">The connection string of the namespace for the specified authorizationRule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-233">Ruft den primären und sekundären ConnectionStrings auf den namespace</span><span class="sxs-lookup"><span data-stu-id="182a1-233">Gets the Primary and Secondary ConnectionStrings to the namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListKeysAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-235">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-235">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-236">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-236">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-237">Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="182a1-237">The connection string of the namespace for the specified authorizationRule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-239">Ruft den primären und sekundären ConnectionStrings auf den namespace</span><span class="sxs-lookup"><span data-stu-id="182a1-239">Gets the Primary and Secondary ConnectionStrings to the namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="182a1-241">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="182a1-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-242">Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".</span><span class="sxs-lookup"><span data-stu-id="182a1-242">Lists the available namespaces within a resourceGroup.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-243">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="182a1-244">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="182a1-244">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-245">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-246">Listet die verfügbaren Namespaces innerhalb einer "ResourceGroup".</span><span class="sxs-lookup"><span data-stu-id="182a1-246">Lists the available namespaces within a resourceGroup.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Patch (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Patch(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Patch(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As NamespacePatchParameters) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Patch (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-248">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-248">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-249">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-249">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-250">Um eine Ressource Namespace patch angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="182a1-250">Parameters supplied to patch a Namespace Resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-251">Patches für den vorhandenen namespace</span><span class="sxs-lookup"><span data-stu-id="182a1-251">Patches the existing namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; PatchAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; PatchAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.PatchAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.PatchAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;PatchAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-253">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-253">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-254">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-254">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-255">Um eine Ressource Namespace patch angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="182a1-255">Parameters supplied to patch a Namespace Resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-256">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-257">Patches für den vorhandenen namespace</span><span class="sxs-lookup"><span data-stu-id="182a1-257">Patches the existing namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As PolicykeyResource) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-258">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-258">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-259">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-259">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-260">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-260">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-261">Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="182a1-261">The connection string of the namespace for the specified authorizationRule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-262">Der Parameter angegeben, um den Namespace Autorisierung Regelschlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="182a1-262">Parameters supplied to regenerate the Namespace Authorization Rule Key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-263">Generiert die primäre/sekundäre Schlüssel die Namespace-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="182a1-263">Regenerates the Primary/Secondary Keys to the Namespace Authorization Rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="182a1-264">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="182a1-264">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="182a1-265">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="182a1-265">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="182a1-266">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="182a1-266">The namespace name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="182a1-267">Die Verbindungszeichenfolge des Namespaces für die angegebene AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="182a1-267">The connection string of the namespace for the specified authorizationRule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="182a1-268">Der Parameter angegeben, um den Namespace Autorisierung Regelschlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="182a1-268">Parameters supplied to regenerate the Namespace Authorization Rule Key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="182a1-269">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="182a1-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="182a1-270">Generiert die primäre/sekundäre Schlüssel die Namespace-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="182a1-270">Regenerates the Primary/Secondary Keys to the Namespace Authorization Rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>