<Type Name="SubscriptionDefinitionsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionDefinitionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsOperationsExtensions = class" />
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
            <span data-ttu-id="7067f-101">Erweiterungsmethoden für SubscriptionDefinitionsOperations.</span><span class="sxs-lookup"><span data-stu-id="7067f-101">Extension methods for SubscriptionDefinitionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition BeginCreate (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition BeginCreate(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String, body As SubscriptionDefinition) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreate (operations, subscriptionDefinitionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="7067f-103">Der Name der Definition des Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-103">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="7067f-104">Die Erstellung des Abonnements Definition.</span><span class="sxs-lookup"><span data-stu-id="7067f-104">The subscription definition creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-105">Erstellen Sie die Definition einer Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-105">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; BeginCreateAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; BeginCreateAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreateAsync (operations, subscriptionDefinitionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-106">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="7067f-107">Der Name der Definition des Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-107">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="7067f-108">Die Erstellung des Abonnements Definition.</span><span class="sxs-lookup"><span data-stu-id="7067f-108">The subscription definition creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7067f-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7067f-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-110">Erstellen Sie die Definition einer Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-110">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Create (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Create(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Create(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String, body As SubscriptionDefinition) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Create (operations, subscriptionDefinitionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-111">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="7067f-112">Der Name der Definition des Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-112">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="7067f-113">Die Erstellung des Abonnements Definition.</span><span class="sxs-lookup"><span data-stu-id="7067f-113">The subscription definition creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-114">Erstellen Sie die Definition einer Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-114">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; CreateAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; CreateAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.CreateAsync (operations, subscriptionDefinitionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-115">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="7067f-116">Der Name der Definition des Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-116">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="7067f-117">Die Erstellung des Abonnements Definition.</span><span class="sxs-lookup"><span data-stu-id="7067f-117">The subscription definition creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7067f-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7067f-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-119">Erstellen Sie die Definition einer Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-119">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Get (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Get(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Get (operations, subscriptionDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-120">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="7067f-121">Der Name der Definition des Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-121">The name of the Azure subscription definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-122">Rufen Sie die Definition einer Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-122">Get an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetAsync (operations, subscriptionDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-123">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="7067f-124">Der Name der Definition des Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-124">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7067f-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7067f-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-126">Rufen Sie die Definition einer Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="7067f-126">Get an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition GetOperationStatus (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition GetOperationStatus(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatus(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatus (operations As ISubscriptionDefinitionsOperations, operationId As Guid) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member GetOperationStatus : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * Guid -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatus (operations, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-127">The operations group for this extension method.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="7067f-128">Die Vorgangs-ID, die im Antwortheader generieren Empfehlung aus dem Feld "Speicherort" befinden.</span><span class="sxs-lookup"><span data-stu-id="7067f-128">The operation ID, which can be found from the Location field in the generate recommendation response header.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-129">Ruft den Status der Abonnementdefinition PUT-Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="7067f-129">Retrieves the status of the subscription definition PUT operation.</span></span> <span data-ttu-id="7067f-130">Der URI dieser API wird in das Feld "Speicherort" in der Antwortheader zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7067f-130">The URI of this API is returned in the Location field of the response header.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetOperationStatusAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, Guid operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetOperationStatusAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatusAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOperationStatusAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatusAsync (operations, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;GetOperationStatusAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-131">The operations group for this extension method.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="7067f-132">Die Vorgangs-ID, die im Antwortheader generieren Empfehlung aus dem Feld "Speicherort" befinden.</span><span class="sxs-lookup"><span data-stu-id="7067f-132">The operation ID, which can be found from the Location field in the generate recommendation response header.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7067f-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7067f-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-134">Ruft den Status der Abonnementdefinition PUT-Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="7067f-134">Retrieves the status of the subscription definition PUT operation.</span></span> <span data-ttu-id="7067f-135">Der URI dieser API wird in das Feld "Speicherort" in der Antwortheader zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7067f-135">The URI of this API is returned in the Location field of the response header.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; List (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; List(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISubscriptionDefinitionsOperations) As IPage(Of SubscriptionDefinition)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-136">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-137">Auflisten der Definition einer Azure-Abonnement "subscriptionId".</span><span class="sxs-lookup"><span data-stu-id="7067f-137">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-138">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7067f-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7067f-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-140">Auflisten der Definition einer Azure-Abonnement "subscriptionId".</span><span class="sxs-lookup"><span data-stu-id="7067f-140">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISubscriptionDefinitionsOperations, nextPageLink As String) As IPage(Of SubscriptionDefinition)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-141">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7067f-142">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7067f-142">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-143">Auflisten der Definition einer Azure-Abonnement "subscriptionId".</span><span class="sxs-lookup"><span data-stu-id="7067f-143">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7067f-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7067f-144">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7067f-145">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7067f-145">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7067f-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7067f-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7067f-147">Auflisten der Definition einer Azure-Abonnement "subscriptionId".</span><span class="sxs-lookup"><span data-stu-id="7067f-147">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>