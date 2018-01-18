<Type Name="SubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionsOperationsExtensions = class" />
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
            <span data-ttu-id="6d9ed-101">Erweiterungsmethoden für SubscriptionsOperations.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-101">Extension methods for SubscriptionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.Subscription Get (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.Subscription Get(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubscriptionsOperations, subscriptionId As String) As Subscription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Subscription" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.Get (operations, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Subscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-102">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionId">
            <span data-ttu-id="6d9ed-103">Die ID des Ziel-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-103">The ID of the target subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-104">Ruft Details zu einem angegebenen Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-104">Gets details about a specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.GetAsync (operations, subscriptionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-105">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionId">
            <span data-ttu-id="6d9ed-106">Die ID des Ziel-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-106">The ID of the target subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d9ed-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-108">Ruft Details zu einem angegebenen Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-108">Gets details about a specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt; List (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt; List(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISubscriptionsOperations) As IPage(Of Subscription)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-109">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-110">Ruft alle Abonnements für einen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-110">Gets all subscriptions for a tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-111">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d9ed-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-113">Ruft alle Abonnements für einen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-113">Gets all subscriptions for a tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLocations">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Models.Location&gt; ListLocations (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Location&gt; ListLocations(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListLocations(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLocations (operations As ISubscriptionsOperations, subscriptionId As String) As IEnumerable(Of Location)" />
      <MemberSignature Language="F#" Value="static member ListLocations : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.ResourceManager.Models.Location&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListLocations (operations, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Models.Location&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-114">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionId">
            <span data-ttu-id="6d9ed-115">Die ID des Ziel-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-115">The ID of the target subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-116">Ruft alle verfügbaren geolocations.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-116">Gets all available geo-locations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6d9ed-117">Dieser Vorgang bietet allen Standorten, die für Ressourcenanbieter verfügbar sind. jedem Ressourcenanbieter unterstützt jedoch möglicherweise eine Teilmenge dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-117">This operation provides all the locations that are available for resource providers; however, each resource provider may support a subset of this list.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLocationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Models.Location&gt;&gt; ListLocationsAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Location&gt;&gt; ListLocationsAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string subscriptionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListLocationsAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLocationsAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.ResourceManager.Models.Location&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListLocationsAsync (operations, subscriptionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions/&lt;ListLocationsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Models.Location&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-118">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionId">
            <span data-ttu-id="6d9ed-119">Die ID des Ziel-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-119">The ID of the target subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d9ed-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-121">Ruft alle verfügbaren geolocations.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-121">Gets all available geo-locations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6d9ed-122">Dieser Vorgang bietet allen Standorten, die für Ressourcenanbieter verfügbar sind. jedem Ressourcenanbieter unterstützt jedoch möglicherweise eine Teilmenge dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-122">This operation provides all the locations that are available for resource providers; however, each resource provider may support a subset of this list.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISubscriptionsOperations, nextPageLink As String) As IPage(Of Subscription)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-123">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6d9ed-124">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-124">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-125">Ruft alle Abonnements für einen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-125">Gets all subscriptions for a tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionsOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Subscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d9ed-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-126">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6d9ed-127">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-127">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d9ed-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d9ed-129">Ruft alle Abonnements für einen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="6d9ed-129">Gets all subscriptions for a tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>