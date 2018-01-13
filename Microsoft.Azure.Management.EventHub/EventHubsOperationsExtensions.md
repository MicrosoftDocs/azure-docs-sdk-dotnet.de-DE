<Type Name="EventHubsOperationsExtensions" FullName="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EventHubsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventHubsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventHubsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EventHubsOperationsExtensions = class" />
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
            <span data-ttu-id="2f8e4-101">Erweiterungsmethoden für EventHubsOperations.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-101">Extension methods for EventHubsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.Eventhub CreateOrUpdate (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, Microsoft.Azure.Management.EventHub.Models.Eventhub parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.Eventhub CreateOrUpdate(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, class Microsoft.Azure.Management.EventHub.Models.Eventhub parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.Eventhub)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, parameters As Eventhub) As Eventhub" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.Eventhub -&gt; Microsoft.Azure.Management.EventHub.Models.Eventhub" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, eventHubName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.Eventhub</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.Eventhub" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-103">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-104">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-104">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-105">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-105">The Event Hub name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2f8e4-106">Parameter zum Erstellen einer Event Hub-Ressource angegeben.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-106">Parameters supplied to create an Event Hub resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-107">Erstellt oder aktualisiert einen neuen Event Hub als eine geschachtelte Ressource in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-107">Creates or updates a new Event Hub as a nested resource within a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, Microsoft.Azure.Management.EventHub.Models.Eventhub parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, class Microsoft.Azure.Management.EventHub.Models.Eventhub parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.Eventhub,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.Eventhub * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, eventHubName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.Eventhub" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-109">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-109">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-110">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-110">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-111">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-111">The Event Hub name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2f8e4-112">Parameter zum Erstellen einer Event Hub-Ressource angegeben.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-112">Parameters supplied to create an Event Hub resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-114">Erstellt oder aktualisiert einen neuen Event Hub als eine geschachtelte Ressource in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-114">Creates or updates a new Event Hub as a nested resource within a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AuthorizationRule CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, authorizationRuleName As String, parameters As AuthorizationRule) As AuthorizationRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string * Microsoft.Azure.Management.EventHub.Models.AuthorizationRule -&gt; Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-116">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-116">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-117">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-117">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-118">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-118">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-119">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-119">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2f8e4-120">Die SAS AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-120">The shared access AuthorizationRule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-121">Erstellt oder aktualisiert eine AuthorizationRule für den angegebenen Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-121">Creates or updates an AuthorizationRule for the specified Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.AuthorizationRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string * Microsoft.Azure.Management.EventHub.Models.AuthorizationRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-123">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-123">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-124">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-124">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-125">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-125">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-126">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-126">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2f8e4-127">Die SAS AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-127">The shared access AuthorizationRule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-129">Erstellt oder aktualisiert eine AuthorizationRule für den angegebenen Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-129">Creates or updates an AuthorizationRule for the specified Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.Delete(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, eventHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-131">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-131">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-132">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-132">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-133">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-133">The Event Hub name</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-134">Löscht einen Event Hub aus der angegebenen Namespace und der Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-134">Deletes an Event Hub from the specified Namespace and resource group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, eventHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-136">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-136">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-137">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-137">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-138">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-138">The Event Hub name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-140">Löscht einen Event Hub aus der angegebenen Namespace und der Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-140">Deletes an Event Hub from the specified Namespace and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-142">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-142">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-143">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-143">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-144">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-144">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-145">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-145">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-146">Löscht einen Event Hub-AuthorizationRule an.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-146">Deletes an Event Hub AuthorizationRule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-148">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-148">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-149">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-149">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-150">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-150">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-151">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-151">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-153">Löscht einen Event Hub-AuthorizationRule an.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-153">Deletes an Event Hub AuthorizationRule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.Eventhub Get (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.Eventhub Get(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.Get(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String) As Eventhub" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.Eventhub" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, eventHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.Eventhub</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-155">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-155">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-156">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-156">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-157">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-157">The Event Hub name</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-158">Ruft eine Beschreibung des Event Hubs für den angegebenen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-158">Gets an Event Hubs description for the specified Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; GetAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; GetAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, eventHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-160">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-160">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-161">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-161">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-162">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-162">The Event Hub name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-164">Ruft eine Beschreibung des Event Hubs für den angegebenen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-164">Gets an Event Hubs description for the specified Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AuthorizationRule GetAuthorizationRule (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule GetAuthorizationRule(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, authorizationRuleName As String) As AuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-166">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-166">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-167">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-167">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-168">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-168">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-169">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-169">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-170">Ruft eine AuthorizationRule für einen Event Hub nach Regelname ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-170">Gets an AuthorizationRule for an Event Hub by rule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-172">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-172">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-173">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-173">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-174">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-174">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-175">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-175">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-177">Ruft eine AuthorizationRule für einen Event Hub nach Regelname ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-177">Gets an AuthorizationRule for an Event Hub by rule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRules (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRules(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String) As IPage(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName, eventHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-179">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-179">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-180">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-180">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-181">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-181">The Event Hub name</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-182">Ruft die Autorisierungsregeln für einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-182">Gets the authorization rules for an Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, eventHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-184">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-184">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-185">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-185">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-186">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-186">The Event Hub name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-188">Ruft die Autorisierungsregeln für einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-188">Gets the authorization rules for an Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As IEventHubsOperations, nextPageLink As String) As IPage(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-189">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2f8e4-190">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-190">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-191">Ruft die Autorisierungsregeln für einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-191">Gets the authorization rules for an Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-192">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2f8e4-193">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-193">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-195">Ruft die Autorisierungsregeln für einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-195">Gets the authorization rules for an Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; ListByNamespace (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; ListByNamespace(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespace(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespace (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String) As IPage(Of Eventhub)" />
      <MemberSignature Language="F#" Value="static member ListByNamespace : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespace (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-197">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-197">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-198">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-198">The Namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-199">Ruft alle Event Hubs in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-199">Gets all the Event Hubs in a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt; ListByNamespaceAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt; ListByNamespaceAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespaceAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespaceAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;ListByNamespaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-201">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-201">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-202">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-202">The Namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-204">Ruft alle Event Hubs in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-204">Gets all the Event Hubs in a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; ListByNamespaceNext (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.Eventhub&gt; ListByNamespaceNext(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespaceNext(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespaceNext (operations As IEventHubsOperations, nextPageLink As String) As IPage(Of Eventhub)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNext : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2f8e4-206">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-207">Ruft alle Event Hubs in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-207">Gets all the Event Hubs in a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt; ListByNamespaceNextAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt; ListByNamespaceNextAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespaceNextAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNextAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListByNamespaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;ListByNamespaceNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.Eventhub&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-208">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2f8e4-209">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-209">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-211">Ruft alle Event Hubs in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-211">Gets all the Event Hubs in a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AccessKeys ListKeys (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AccessKeys ListKeys(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListKeys(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, authorizationRuleName As String) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.AccessKeys" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-213">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-213">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-214">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-214">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-215">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-215">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-216">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-216">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-217">Ruft die ACS und SAS-Verbindungszeichenfolgen für den Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-217">Gets the ACS and SAS connection strings for the Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;ListKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-219">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-219">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-220">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-220">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-221">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-221">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-222">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-222">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-223">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-224">Ruft die ACS und SAS-Verbindungszeichenfolgen für den Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-224">Gets the ACS and SAS connection strings for the Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AccessKeys RegenerateKeys (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AccessKeys RegenerateKeys(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, authorizationRuleName As String, parameters As RegenerateAccessKeyParameters) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string * Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters -&gt; Microsoft.Azure.Management.EventHub.Models.AccessKeys" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-226">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-226">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-227">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-227">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-228">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-228">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-229">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-229">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2f8e4-230">Parameter, die zum erneuten Generieren der AuthorizationRule-Schlüssel (PrimaryKey/SecondaryKey) angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-230">Parameters supplied to regenerate the AuthorizationRule Keys (PrimaryKey/SecondaryKey).</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-231">Generiert einen neuen ACS und SAS-Verbindungszeichenfolgen für den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-231">Regenerates the ACS and SAS connection strings for the Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.EventHub.IEventHubsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.EventHub.IEventHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.EventHub.IEventHubsOperations * string * string * string * string * Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, eventHubName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.EventHubsOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f8e4-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2f8e4-233">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-233">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2f8e4-234">Der Namespace-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-234">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2f8e4-235">Der Event Hub-name</span><span class="sxs-lookup"><span data-stu-id="2f8e4-235">The Event Hub name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="2f8e4-236">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-236">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2f8e4-237">Parameter, die zum erneuten Generieren der AuthorizationRule-Schlüssel (PrimaryKey/SecondaryKey) angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-237">Parameters supplied to regenerate the AuthorizationRule Keys (PrimaryKey/SecondaryKey).</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2f8e4-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f8e4-239">Generiert einen neuen ACS und SAS-Verbindungszeichenfolgen für den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2f8e4-239">Regenerates the ACS and SAS connection strings for the Event Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>