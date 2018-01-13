<Type Name="DisasterRecoveryConfigsOperationsExtensions" FullName="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DisasterRecoveryConfigsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DisasterRecoveryConfigsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DisasterRecoveryConfigsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DisasterRecoveryConfigsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0ecdd-101">Erweiterungsmethoden für DisasterRecoveryConfigsOperations.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-101">Extension methods for DisasterRecoveryConfigsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BreakPairing">
      <MemberSignature Language="C#" Value="public static void BreakPairing (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BreakPairing(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.BreakPairing(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BreakPairing (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String)" />
      <MemberSignature Language="F#" Value="static member BreakPairing : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.BreakPairing (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-103">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-104">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-104">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-105">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-105">The Disaster Recovery configuration name</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-106">Durch diesen Vorgang der Wiederherstellung im Notfall deaktiviert und beendet das Replizieren von Änderungen vom primären zum sekundären namespaces</span><span class="sxs-lookup"><span data-stu-id="0ecdd-106">This operation disables the Disaster Recovery and stops replicating changes from primary to secondary namespaces</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakPairingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BreakPairingAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BreakPairingAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.BreakPairingAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BreakPairingAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.BreakPairingAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;BreakPairingAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-108">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-108">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-109">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-109">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-110">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-110">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-112">Durch diesen Vorgang der Wiederherstellung im Notfall deaktiviert und beendet das Replizieren von Änderungen vom primären zum sekundären namespaces</span><span class="sxs-lookup"><span data-stu-id="0ecdd-112">This operation disables the Disaster Recovery and stops replicating changes from primary to secondary namespaces</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult CheckNameAvailability (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult CheckNameAvailability(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, parameters As CheckNameAvailabilityParameter) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter -&gt; Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailability (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-114">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-114">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-115">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-115">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ecdd-116">Parameter für die Verfügbarkeit von den angegebenen Aliasnamen überprüfen</span><span class="sxs-lookup"><span data-stu-id="0ecdd-116">Parameters to check availability of the given Alias name</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-117">Überprüfen Sie die Verfügbarkeit eines Namespace erteilen.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-117">Check the give Namespace name availability.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailabilityAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-119">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-119">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-120">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-120">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ecdd-121">Parameter für die Verfügbarkeit von den angegebenen Aliasnamen überprüfen</span><span class="sxs-lookup"><span data-stu-id="0ecdd-121">Parameters to check availability of the given Alias name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-123">Überprüfen Sie die Verfügbarkeit eines Namespace erteilen.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-123">Check the give Namespace name availability.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery CreateOrUpdate (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery CreateOrUpdate(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String, parameters As ArmDisasterRecovery) As ArmDisasterRecovery" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery -&gt; Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, alias, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-125">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-125">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-126">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-126">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-127">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-127">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ecdd-128">So erstellen Sie einen Alias (Wiederherstellung im Notfall-Konfiguration) erforderlichen Parametern</span><span class="sxs-lookup"><span data-stu-id="0ecdd-128">Parameters required to create an Alias(Disaster Recovery configuration)</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-129">Erstellt oder aktualisiert einen neuen Alias (Wiederherstellung im Notfall-Konfiguration)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-129">Creates or updates a new Alias(Disaster Recovery configuration)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, alias, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-131">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-131">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-132">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-132">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-133">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-133">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ecdd-134">So erstellen Sie einen Alias (Wiederherstellung im Notfall-Konfiguration) erforderlichen Parametern</span><span class="sxs-lookup"><span data-stu-id="0ecdd-134">Parameters required to create an Alias(Disaster Recovery configuration)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-136">Erstellt oder aktualisiert einen neuen Alias (Wiederherstellung im Notfall-Konfiguration)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-136">Creates or updates a new Alias(Disaster Recovery configuration)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.Delete(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-138">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-138">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-139">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-139">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-140">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-140">The Disaster Recovery configuration name</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-141">Löscht einen Alias (Wiederherstellung im Notfall-Konfiguration)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-141">Deletes an Alias(Disaster Recovery configuration)</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-143">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-143">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-144">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-144">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-145">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-145">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-147">Löscht einen Alias (Wiederherstellung im Notfall-Konfiguration)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-147">Deletes an Alias(Disaster Recovery configuration)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailOver">
      <MemberSignature Language="C#" Value="public static void FailOver (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void FailOver(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.FailOver(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub FailOver (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String)" />
      <MemberSignature Language="F#" Value="static member FailOver : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.FailOver (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-149">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-149">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-150">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-150">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-151">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-151">The Disaster Recovery configuration name</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-152">Envokes GEO-DR-Failover und konfigurieren Sie den Aliasnamen an, zeigen Sie auf den sekundären Namespace neu.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-152">envokes GEO DR failover and reconfigure the alias to point to the secondary namespace</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailOverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailOverAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailOverAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.FailOverAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailOverAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.FailOverAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;FailOverAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-154">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-154">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-155">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-155">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-156">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-156">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-158">Envokes GEO-DR-Failover und konfigurieren Sie den Aliasnamen an, zeigen Sie auf den sekundären Namespace neu.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-158">envokes GEO DR failover and reconfigure the alias to point to the secondary namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery Get (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery Get(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.Get(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String) As ArmDisasterRecovery" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-160">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-160">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-161">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-161">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-162">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-162">The Disaster Recovery configuration name</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-163">Ruft ab Alias (Wiederherstellung im Notfall-Konfiguration) für den primären oder sekundären namespace</span><span class="sxs-lookup"><span data-stu-id="0ecdd-163">Retrieves Alias(Disaster Recovery configuration) for primary or secondary namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; GetAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; GetAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-165">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-165">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-166">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-166">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-167">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-167">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-169">Ruft ab Alias (Wiederherstellung im Notfall-Konfiguration) für den primären oder sekundären namespace</span><span class="sxs-lookup"><span data-stu-id="0ecdd-169">Retrieves Alias(Disaster Recovery configuration) for primary or secondary namespace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AuthorizationRule GetAuthorizationRule (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule GetAuthorizationRule(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String, authorizationRuleName As String) As AuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, alias, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-171">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-171">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-172">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-172">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-173">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-173">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ecdd-174">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-174">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-175">Ruft eine AuthorizationRule für einen Namespace nach Regelname ab.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-175">Gets an AuthorizationRule for a Namespace by rule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, alias, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-177">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-177">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-178">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-178">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-179">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-179">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ecdd-180">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-180">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-182">Ruft eine AuthorizationRule für einen Namespace nach Regelname ab.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-182">Gets an AuthorizationRule for a Namespace by rule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; List (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; List(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.List(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String) As IPage(Of ArmDisasterRecovery)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.List (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-184">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-184">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-185">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-185">The Namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-186">Ruft alle Alias (Wiederherstellung im Notfall Konfigurationen)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-186">Gets all Alias(Disaster Recovery configurations)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt; ListAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt; ListAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-188">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-188">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-189">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-189">The Namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-191">Ruft alle Alias (Wiederherstellung im Notfall Konfigurationen)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-191">Gets all Alias(Disaster Recovery configurations)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRules (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRules(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String) As IPage(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-193">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-193">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-194">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-194">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-195">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-195">The Disaster Recovery configuration name</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-196">Ruft eine Liste von Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-196">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-198">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-198">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-199">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-199">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-200">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-200">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-201">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-202">Ruft eine Liste von Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-202">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As IDisasterRecoveryConfigsOperations, nextPageLink As String) As IPage(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-203">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-203">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0ecdd-204">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-205">Ruft eine Liste von Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-205">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-206">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0ecdd-207">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-207">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-209">Ruft eine Liste von Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-209">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AccessKeys ListKeys (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AccessKeys ListKeys(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListKeys(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String, authorizationRuleName As String) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.AccessKeys" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, alias, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-211">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-211">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-212">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-212">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-213">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-213">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ecdd-214">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-214">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-215">Ruft die primären und sekundären Verbindungszeichenfolgen für den Namespace ab.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-215">Gets the primary and secondary connection strings for the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, alias, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;ListKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ecdd-217">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-217">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="0ecdd-218">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="0ecdd-218">The Namespace name</span></span>
            </param>
        <param name="alias">
            <span data-ttu-id="0ecdd-219">Der Konfigurationsname für die Wiederherstellung im Notfall</span><span class="sxs-lookup"><span data-stu-id="0ecdd-219">The Disaster Recovery configuration name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="0ecdd-220">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-220">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-222">Ruft die primären und sekundären Verbindungszeichenfolgen für den Namespace ab.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-222">Gets the primary and secondary connection strings for the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; ListNext (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt; ListNext(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListNext(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDisasterRecoveryConfigsOperations, nextPageLink As String) As IPage(Of ArmDisasterRecovery)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-223">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0ecdd-224">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-224">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-225">Ruft alle Alias (Wiederherstellung im Notfall Konfigurationen)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-225">Gets all Alias(Disaster Recovery configurations)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.DisasterRecoveryConfigsOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ecdd-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-226">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0ecdd-227">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-227">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ecdd-228">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ecdd-229">Ruft alle Alias (Wiederherstellung im Notfall Konfigurationen)</span><span class="sxs-lookup"><span data-stu-id="0ecdd-229">Gets all Alias(Disaster Recovery configurations)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>