<Type Name="WebhooksOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WebhooksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebhooksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebhooksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WebhooksOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c6a6c-101">Erweiterungsmethoden für WebhooksOperations.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-101">Extension methods for WebhooksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginCreate (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginCreate(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreate (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-103">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-103">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-104">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-104">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-105">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-105">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="c6a6c-106">Die Parameter für Webhook erstellen.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-106">The parameters for creating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-107">Erstellt einen Webhook für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-107">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginCreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginCreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;BeginCreateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-109">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-109">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-110">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-110">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-111">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-111">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="c6a6c-112">Die Parameter für Webhook erstellen.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-112">The parameters for creating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-114">Erstellt einen Webhook für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-114">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDelete (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-116">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-116">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-117">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-117">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-118">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-118">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-119">Löscht einen Webhook aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-119">Deletes a webhook from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-121">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-121">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-122">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-122">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-123">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-123">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-125">Löscht einen Webhook aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-125">Deletes a webhook from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginUpdate (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginUpdate(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdate (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-127">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-127">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-128">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-128">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-129">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-129">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="c6a6c-130">Die Parameter für einen Webhook zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-130">The parameters for updating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-131">Aktualisiert einen Webhook mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-131">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginUpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginUpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;BeginUpdateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-133">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-133">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-134">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-134">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-135">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-135">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="c6a6c-136">Die Parameter für einen Webhook zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-136">The parameters for updating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-138">Aktualisiert einen Webhook mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-138">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Create (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Create(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Create(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Create (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-140">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-140">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-141">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-141">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-142">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-142">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="c6a6c-143">Die Parameter für Webhook erstellen.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-143">The parameters for creating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-144">Erstellt einen Webhook für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-144">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; CreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; CreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.CreateAsync (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-146">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-146">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-147">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-147">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-148">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-148">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="c6a6c-149">Die Parameter für Webhook erstellen.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-149">The parameters for creating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-151">Erstellt einen Webhook für die containerregistrierung eines mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-151">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Delete(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Delete (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-153">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-153">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-154">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-154">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-155">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-155">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-156">Löscht einen Webhook aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-156">Deletes a webhook from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.DeleteAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-158">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-158">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-159">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-159">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-160">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-160">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-162">Löscht einen Webhook aus einer containerregistrierung an.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-162">Deletes a webhook from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Get (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Get(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Get(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As Webhook" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Get (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-164">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-164">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-165">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-165">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-166">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-166">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-167">Ruft die Eigenschaften des angegebenen webhooks ab.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-167">Gets the properties of the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; GetAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; GetAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-169">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-169">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-170">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-170">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-171">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-171">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-173">Ruft die Eigenschaften des angegebenen webhooks ab.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-173">Gets the properties of the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCallbackConfig">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig GetCallbackConfig (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig GetCallbackConfig(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfig(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCallbackConfig (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As CallbackConfig" />
      <MemberSignature Language="F#" Value="static member GetCallbackConfig : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfig (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-175">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-175">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-176">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-176">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-177">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-177">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-178">Ruft die Konfiguration des Dienst-URI und Header für den Webhook ab.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-178">Gets the configuration of service URI and custom headers for the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCallbackConfigAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt; GetCallbackConfigAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt; GetCallbackConfigAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfigAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCallbackConfigAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfigAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;GetCallbackConfigAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-180">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-180">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-181">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-181">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-182">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-182">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-184">Ruft die Konfiguration des Dienst-URI und Header für den Webhook ab.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-184">Gets the configuration of service URI and custom headers for the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; List (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; List(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.List(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWebhooksOperations, resourceGroupName As String, registryName As String) As IPage(Of Webhook)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.List (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-186">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-186">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-187">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-187">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-188">Listet alle Webhooks für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-188">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-190">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-190">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-191">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-191">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-193">Listet alle Webhooks für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-193">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEvents">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEvents (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEvents(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEvents(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEvents (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As IPage(Of EventModel)" />
      <MemberSignature Language="F#" Value="static member ListEvents : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEvents (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-195">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-195">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-196">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-196">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-197">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-197">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-198">Listet die aktuellsten Ereignisse für den angegebenen Webhook.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-198">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventsAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListEventsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-199">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-200">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-200">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-201">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-201">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-202">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-202">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-204">Listet die aktuellsten Ereignisse für den angegebenen Webhook.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-204">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEventsNext (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEventsNext(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNext(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventsNext (operations As IWebhooksOperations, nextPageLink As String) As IPage(Of EventModel)" />
      <MemberSignature Language="F#" Value="static member ListEventsNext : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c6a6c-206">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-207">Listet die aktuellsten Ereignisse für den angegebenen Webhook.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-207">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNextAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventsNextAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListEventsNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-208">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c6a6c-209">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-209">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-211">Listet die aktuellsten Ereignisse für den angegebenen Webhook.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-211">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; ListNext (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; ListNext(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNext(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IWebhooksOperations, nextPageLink As String) As IPage(Of Webhook)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-212">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c6a6c-213">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-213">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-214">Listet alle Webhooks für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-214">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c6a6c-216">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-217">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-218">Listet alle Webhooks für die Registrierung des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-218">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ping">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo Ping (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo Ping(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Ping(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Ping (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As EventInfo" />
      <MemberSignature Language="F#" Value="static member Ping : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Ping (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-219">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-220">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-220">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-221">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-221">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-222">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-222">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-223">Löst ein Ereignis Ping an den Webhook gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-223">Triggers a ping event to be sent to the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt; PingAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt; PingAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.PingAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PingAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.PingAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;PingAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-225">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-225">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-226">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-226">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-227">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-227">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-228">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-229">Löst ein Ereignis Ping an den Webhook gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-229">Triggers a ping event to be sent to the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Update (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Update(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Update(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Update (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-230">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-231">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-231">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-232">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-232">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-233">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-233">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="c6a6c-234">Die Parameter für einen Webhook zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-234">The parameters for updating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-235">Aktualisiert einen Webhook mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-235">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; UpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; UpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.UpdateAsync (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c6a6c-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a6c-237">Der Name der Ressourcengruppe, zu der die containerregistrierung gehört.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-237">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="c6a6c-238">Der Name der der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-238">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="c6a6c-239">Der Name des Webhooks.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-239">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="c6a6c-240">Die Parameter für einen Webhook zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-240">The parameters for updating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a6c-241">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a6c-242">Aktualisiert einen Webhook mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="c6a6c-242">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>