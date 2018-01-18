<Type Name="SubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0f4f-101">Erweiterungsmethoden für SubscriptionsOperations.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-101">Extension methods for SubscriptionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBSubscription CreateOrUpdate (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription CreateOrUpdate(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String, parameters As SBSubscription) As SBSubscription" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBSubscription -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, topicName, subscriptionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-104">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-104">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-105">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-105">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="c0f4f-106">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-106">The subscription name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0f4f-107">Parameter zum Erstellen einer abonnementressource angegeben.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-107">Parameters supplied to create a subscription resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-108">Erstellt ein themenabonnement.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-108">Creates a topic subscription.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639385.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-110">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-110">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-111">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-111">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-112">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-112">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="c0f4f-113">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-113">The subscription name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0f4f-114">Parameter zum Erstellen einer abonnementressource angegeben.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-114">Parameters supplied to create a subscription resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0f4f-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-116">Erstellt ein themenabonnement.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-116">Creates a topic subscription.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639385.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Delete(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, topicName, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-118">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-118">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-119">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-119">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-120">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-120">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="c0f4f-121">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-121">The subscription name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-122">Löscht ein Abonnement aus dem angegebenen Thema.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-122">Deletes a subscription from the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639381.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-124">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-124">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-125">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-125">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-126">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-126">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="c0f4f-127">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-127">The subscription name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0f4f-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-129">Löscht ein Abonnement aus dem angegebenen Thema.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-129">Deletes a subscription from the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639381.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBSubscription Get (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription Get(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Get(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String) As SBSubscription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, topicName, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-131">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-131">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-132">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-132">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-133">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-133">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="c0f4f-134">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-134">The subscription name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-135">Gibt eine abonnementbeschreibung für das angegebene Thema.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-135">Returns a subscription description for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639402.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-137">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-137">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-138">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-138">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-139">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-139">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="c0f4f-140">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-140">The subscription name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0f4f-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-142">Gibt eine abonnementbeschreibung für das angegebene Thema.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-142">Returns a subscription description for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639402.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopic">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopic (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopic(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopic(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByTopic (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String) As IPage(Of SBSubscription)" />
      <MemberSignature Language="F#" Value="static member ListByTopic : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopic (operations, resourceGroupName, namespaceName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-144">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-144">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-145">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-145">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-146">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-146">The topic name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-147">Listen Sie aller Abonnements unter einem angegebenen Thema auf.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-147">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicAsync (operations, resourceGroupName, namespaceName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;ListByTopicAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0f4f-149">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-149">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0f4f-150">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="c0f4f-150">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="c0f4f-151">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-151">The topic name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0f4f-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-153">Listen Sie aller Abonnements unter einem angegebenen Thema auf.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-153">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopicNext (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopicNext(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNext(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByTopicNext (operations As ISubscriptionsOperations, nextPageLink As String) As IPage(Of SBSubscription)" />
      <MemberSignature Language="F#" Value="static member ListByTopicNext : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c0f4f-155">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-156">Listen Sie aller Abonnements unter einem angegebenen Thema auf.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-156">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicNextAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicNextAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNextAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicNextAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;ListByTopicNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0f4f-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-157">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c0f4f-158">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-158">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0f4f-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0f4f-160">Listen Sie aller Abonnements unter einem angegebenen Thema auf.</span><span class="sxs-lookup"><span data-stu-id="c0f4f-160">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>