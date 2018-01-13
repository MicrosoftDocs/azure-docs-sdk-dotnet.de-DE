<Type Name="NotificationHubsOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NotificationHubsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NotificationHubsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NotificationHubsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NotificationHubsOperationsExtensions = class" />
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
            <span data-ttu-id="96e0b-101">Erweiterungsmethoden für NotificationHubsOperations.</span><span class="sxs-lookup"><span data-stu-id="96e0b-101">Extension methods for NotificationHubsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, parameters As CheckAvailabilityParameters) As CheckAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailability (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-103">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-104">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-104">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-105">Der NotificationHub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-105">The notificationHub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-106">Überprüft die Verfügbarkeit von der angegebenen NotificationHub in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="96e0b-106">Checks the availability of the given notificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailabilityAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-108">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-109">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-109">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-110">Der NotificationHub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-110">The notificationHub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-112">Überprüft die Verfügbarkeit von der angegebenen NotificationHub in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="96e0b-112">Checks the availability of the given notificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource CreateOrUpdate (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource CreateOrUpdate(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, parameters As NotificationHubCreateOrUpdateParameters) As NotificationHubResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, notificationHubName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-114">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-115">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-115">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-116">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-116">The notification hub name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-117">Parameter, die das Erstellen/Aktualisieren einer NotificationHub-Ressource bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="96e0b-117">Parameters supplied to the create/update a NotificationHub Resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-118">Eine NotificationHub in einem Namespace erstellt/aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="96e0b-118">Creates/Update a NotificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, notificationHubName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-120">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-121">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-121">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-122">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-122">The notification hub name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-123">Parameter, die das Erstellen/Aktualisieren einer NotificationHub-Ressource bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="96e0b-123">Parameters supplied to the create/update a NotificationHub Resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-125">Eine NotificationHub in einem Namespace erstellt/aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="96e0b-125">Creates/Update a NotificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String, parameters As SharedAccessAuthorizationRuleCreateOrUpdateParameters) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-127">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-128">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-128">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-129">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-129">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-130">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="96e0b-130">Authorization Rule Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-131">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="96e0b-131">The shared access authorization rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-132">Eine Autorisierungsregel für einen NotificationHub Erstellungsvorgänge/Updates</span><span class="sxs-lookup"><span data-stu-id="96e0b-132">Creates/Updates an authorization rule for a NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-134">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-135">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-135">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-136">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-136">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-137">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="96e0b-137">Authorization Rule Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-138">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="96e0b-138">The shared access authorization rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-140">Eine Autorisierungsregel für einen NotificationHub Erstellungsvorgänge/Updates</span><span class="sxs-lookup"><span data-stu-id="96e0b-140">Creates/Updates an authorization rule for a NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Delete(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-142">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-143">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-143">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-144">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-144">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-145">Löscht einen benachrichtigungs-Hub mit einem Namespace verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="96e0b-145">Deletes a notification hub associated with a namespace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-147">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-148">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-148">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-149">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-149">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-151">Löscht einen benachrichtigungs-Hub mit einem Namespace verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="96e0b-151">Deletes a notification hub associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-153">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-153">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-154">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-154">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-155">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-155">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-156">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="96e0b-156">Authorization Rule Name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-157">Löscht eine NotificationHub-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="96e0b-157">Deletes a notificationHub authorization rule</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-159">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-160">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-160">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-161">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-161">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-162">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="96e0b-162">Authorization Rule Name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-164">Löscht eine NotificationHub-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="96e0b-164">Deletes a notificationHub authorization rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource Get (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource Get(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Get(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String) As NotificationHubResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-166">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-166">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-167">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-167">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-168">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-168">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-169">Listet die benachrichtigungshubs, die einen Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-169">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; GetAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; GetAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-171">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-171">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-172">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-172">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-173">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-173">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-175">Listet die benachrichtigungshubs, die einen Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-175">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-177">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-177">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-178">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="96e0b-178">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-179">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-179">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-180">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="96e0b-180">authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-181">Ruft eine Autorisierungsregel für einen NotificationHub nach Namen ab.</span><span class="sxs-lookup"><span data-stu-id="96e0b-181">Gets an authorization rule for a NotificationHub by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-183">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-183">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-184">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="96e0b-184">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-185">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-185">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-186">Autorisierung Regelname.</span><span class="sxs-lookup"><span data-stu-id="96e0b-186">authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-188">Ruft eine Autorisierungsregel für einen NotificationHub nach Namen ab.</span><span class="sxs-lookup"><span data-stu-id="96e0b-188">Gets an authorization rule for a NotificationHub by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPnsCredentials">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource GetPnsCredentials (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource GetPnsCredentials(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentials(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPnsCredentials (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String) As PnsCredentialsResource" />
      <MemberSignature Language="F#" Value="static member GetPnsCredentials : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentials (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-190">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-190">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-191">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-191">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-192">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-192">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-193">Listet die PNS-Anmeldeinformationen, die einen benachrichtigungs-Hub zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-193">Lists the PNS Credentials associated with a notification hub .</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPnsCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt; GetPnsCredentialsAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt; GetPnsCredentialsAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentialsAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPnsCredentialsAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentialsAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;GetPnsCredentialsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-195">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-195">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-196">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-196">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-197">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-197">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-199">Listet die PNS-Anmeldeinformationen, die einen benachrichtigungs-Hub zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-199">Lists the PNS Credentials associated with a notification hub .</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; List (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; List(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.List(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String) As IPage(Of NotificationHubResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.List (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-201">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-201">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-202">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-202">The namespace name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-203">Listet die benachrichtigungshubs, die einen Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-203">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-205">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-205">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-206">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-206">The namespace name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-208">Listet die benachrichtigungshubs, die einen Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-208">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-210">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-210">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-211">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="96e0b-211">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-212">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-212">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-213">Ruft die Autorisierungsregeln für eine NotificationHub ab.</span><span class="sxs-lookup"><span data-stu-id="96e0b-213">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-215">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-215">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-216">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="96e0b-216">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-217">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-217">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-219">Ruft die Autorisierungsregeln für eine NotificationHub ab.</span><span class="sxs-lookup"><span data-stu-id="96e0b-219">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As INotificationHubsOperations, nextPageLink As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-220">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="96e0b-221">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="96e0b-221">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-222">Ruft die Autorisierungsregeln für eine NotificationHub ab.</span><span class="sxs-lookup"><span data-stu-id="96e0b-222">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-223">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="96e0b-224">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="96e0b-224">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-226">Ruft die Autorisierungsregeln für eine NotificationHub ab.</span><span class="sxs-lookup"><span data-stu-id="96e0b-226">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeys(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-228">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-228">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-229">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-229">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-230">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-230">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-231">Die Verbindungszeichenfolge für die NotificationHub für den angegebenen AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="96e0b-231">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-232">Ruft den primären und sekundären ConnectionStrings auf der NotificationHub</span><span class="sxs-lookup"><span data-stu-id="96e0b-232">Gets the Primary and Secondary ConnectionStrings to the NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-234">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-234">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-235">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-235">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-236">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-236">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-237">Die Verbindungszeichenfolge für die NotificationHub für den angegebenen AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="96e0b-237">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-239">Ruft den primären und sekundären ConnectionStrings auf der NotificationHub</span><span class="sxs-lookup"><span data-stu-id="96e0b-239">Gets the Primary and Secondary ConnectionStrings to the NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; ListNext (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; ListNext(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNext(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INotificationHubsOperations, nextPageLink As String) As IPage(Of NotificationHubResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="96e0b-241">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="96e0b-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-242">Listet die benachrichtigungshubs, die einen Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-242">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-243">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="96e0b-244">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="96e0b-244">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-245">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-246">Listet die benachrichtigungshubs, die einen Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="96e0b-246">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String, parameters As PolicykeyResource) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-248">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-248">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-249">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-249">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-250">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-250">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-251">Die Verbindungszeichenfolge für die NotificationHub für den angegebenen AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="96e0b-251">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-252">Der Parameter angegeben wird, um die Regel NotificationHub Autorisierungsschlüssel erneut zu generieren.</span><span class="sxs-lookup"><span data-stu-id="96e0b-252">Parameters supplied to regenerate the NotificationHub Authorization Rule Key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-253">Generiert die primär/Sekundär-Schlüssel in NotificationHub-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="96e0b-253">Regenerates the Primary/Secondary Keys to the NotificationHub Authorization Rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96e0b-254">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96e0b-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96e0b-255">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="96e0b-255">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="96e0b-256">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="96e0b-256">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="96e0b-257">Notification Hub-Name.</span><span class="sxs-lookup"><span data-stu-id="96e0b-257">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="96e0b-258">Die Verbindungszeichenfolge für die NotificationHub für den angegebenen AuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="96e0b-258">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96e0b-259">Der Parameter angegeben wird, um die Regel NotificationHub Autorisierungsschlüssel erneut zu generieren.</span><span class="sxs-lookup"><span data-stu-id="96e0b-259">Parameters supplied to regenerate the NotificationHub Authorization Rule Key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96e0b-260">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96e0b-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96e0b-261">Generiert die primär/Sekundär-Schlüssel in NotificationHub-Autorisierungsregel</span><span class="sxs-lookup"><span data-stu-id="96e0b-261">Regenerates the Primary/Secondary Keys to the NotificationHub Authorization Rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>