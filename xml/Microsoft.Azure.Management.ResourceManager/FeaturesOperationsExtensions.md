<Type Name="FeaturesOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FeaturesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FeaturesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FeaturesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FeaturesOperationsExtensions = class" />
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
            <span data-ttu-id="3d432-101">Erweiterungsmethoden für FeaturesOperations.</span><span class="sxs-lookup"><span data-stu-id="3d432-101">Extension methods for FeaturesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Get (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Get(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFeaturesOperations, resourceProviderNamespace As String, featureName As String) As FeatureResult" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Get (operations, resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.FeatureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="3d432-103">Der Namespace des Ressourcenanbieters für die Funktion.</span><span class="sxs-lookup"><span data-stu-id="3d432-103">The resource provider namespace for the feature.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="3d432-104">Der Name der abzurufenden Funktion.</span><span class="sxs-lookup"><span data-stu-id="3d432-104">The name of the feature to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-105">Ruft die Preview-Funktion mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="3d432-105">Gets the preview feature with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.GetAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-106">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="3d432-107">Der Namespace des Ressourcenanbieters für die Funktion.</span><span class="sxs-lookup"><span data-stu-id="3d432-107">The resource provider namespace for the feature.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="3d432-108">Der Name der abzurufenden Funktion.</span><span class="sxs-lookup"><span data-stu-id="3d432-108">The name of the feature to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d432-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d432-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-110">Ruft die Preview-Funktion mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="3d432-110">Gets the preview feature with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; List (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; List(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IFeaturesOperations, resourceProviderNamespace As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.List (operations, resourceProviderNamespace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="3d432-112">Der Namespace des Ressourcenanbieters zum Abrufen von Funktionen.</span><span class="sxs-lookup"><span data-stu-id="3d432-112">The namespace of the resource provider for getting features.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-113">Ruft alle vorschaufeatures in einem Anbieternamespace, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-113">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAll (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAll(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAll(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IFeaturesOperations) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-114">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-115">Ruft die Preview-Funktionen, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-115">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAllAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-116">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d432-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d432-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-118">Ruft die Preview-Funktionen, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-118">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAllNext (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAllNext(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IFeaturesOperations, nextPageLink As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-119">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3d432-120">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3d432-120">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-121">Ruft die Preview-Funktionen, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-121">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAllNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3d432-123">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3d432-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d432-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d432-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-125">Ruft die Preview-Funktionen, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-125">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="3d432-127">Der Namespace des Ressourcenanbieters zum Abrufen von Funktionen.</span><span class="sxs-lookup"><span data-stu-id="3d432-127">The namespace of the resource provider for getting features.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d432-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d432-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-129">Ruft alle vorschaufeatures in einem Anbieternamespace, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-129">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IFeaturesOperations, nextPageLink As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-130">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3d432-131">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3d432-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-132">Ruft alle vorschaufeatures in einem Anbieternamespace, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-132">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3d432-134">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3d432-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d432-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d432-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-136">Ruft alle vorschaufeatures in einem Anbieternamespace, die über AFEC für das Abonnement zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="3d432-136">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Register (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Register(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Register(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Register (operations As IFeaturesOperations, resourceProviderNamespace As String, featureName As String) As FeatureResult" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Register (operations, resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.FeatureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="3d432-138">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="3d432-138">The namespace of the resource provider.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="3d432-139">Der Name der Funktion zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="3d432-139">The name of the feature to register.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-140">Registriert die Vorschaufunktion für das Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="3d432-140">Registers the preview feature for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;RegisterAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3d432-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3d432-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="3d432-142">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="3d432-142">The namespace of the resource provider.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="3d432-143">Der Name der Funktion zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="3d432-143">The name of the feature to register.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3d432-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3d432-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3d432-145">Registriert die Vorschaufunktion für das Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="3d432-145">Registers the preview feature for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>