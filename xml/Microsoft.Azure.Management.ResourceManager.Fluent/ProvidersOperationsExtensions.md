<Type Name="ProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProvidersOperationsExtensions = class" />
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
            <span data-ttu-id="9b09c-101">Erweiterungsmethoden für ProvidersOperations.</span><span class="sxs-lookup"><span data-stu-id="9b09c-101">Extension methods for ProvidersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.GetAsync (operations, resourceProviderNamespace, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9b09c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9b09c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="9b09c-103">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="9b09c-103">Namespace of the resource provider.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="9b09c-104">Die $expand-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="9b09c-104">The $expand query parameter.</span></span> <span data-ttu-id="9b09c-105">z. B. für die Einbeziehung der Eigenschaft Aliase in der Antwort verwenden $expand-= Ressourcentypen/Aliase.</span><span class="sxs-lookup"><span data-stu-id="9b09c-105">e.g. To include property aliases in response, use $expand=resourceTypes/aliases.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b09c-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9b09c-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b09c-107">Ruft einen Ressourcenanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="9b09c-107">Gets a resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, Nullable&lt;int&gt; top = null, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListAsync (operations, top, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;ListAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9b09c-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9b09c-108">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="9b09c-109">Abfrageparameter an.</span><span class="sxs-lookup"><span data-stu-id="9b09c-109">Query parameters.</span></span> <span data-ttu-id="9b09c-110">Werden alle Bereitstellungen angegeben, wenn Null übergeben wird.</span><span class="sxs-lookup"><span data-stu-id="9b09c-110">If null is passed returns all deployments.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="9b09c-111">Die $expand-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="9b09c-111">The $expand query parameter.</span></span> <span data-ttu-id="9b09c-112">z. B. für die Einbeziehung der Eigenschaft Aliase in der Antwort verwenden $expand-= Ressourcentypen/Aliase.</span><span class="sxs-lookup"><span data-stu-id="9b09c-112">e.g. To include property aliases in response, use $expand=resourceTypes/aliases.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b09c-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9b09c-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b09c-114">Ruft eine Liste der Ressourcenanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="9b09c-114">Gets a list of resource providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;ListNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9b09c-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9b09c-115">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9b09c-116">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9b09c-116">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b09c-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9b09c-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b09c-118">Ruft eine Liste der Ressourcenanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="9b09c-118">Gets a list of resource providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;RegisterAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9b09c-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9b09c-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="9b09c-120">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="9b09c-120">Namespace of the resource provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b09c-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9b09c-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b09c-122">Register-Anbieter mit einem Abonnement verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="9b09c-122">Registers provider to be used with a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; UnregisterAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; UnregisterAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.UnregisterAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnregisterAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.UnregisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;UnregisterAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9b09c-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9b09c-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="9b09c-124">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="9b09c-124">Namespace of the resource provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b09c-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9b09c-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b09c-126">Hebt die Registrierung Anbieter aus einem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="9b09c-126">Unregisters provider from a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>