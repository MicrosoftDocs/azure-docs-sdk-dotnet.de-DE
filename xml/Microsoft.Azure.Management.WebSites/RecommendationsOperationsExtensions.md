<Type Name="RecommendationsOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5d0aa-101">Erweiterungsmethoden für RecommendationsOperations.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-101">Extension methods for RecommendationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableAllForWebApp">
      <MemberSignature Language="C#" Value="public static void DisableAllForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DisableAllForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DisableAllForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebApp (operations, resourceGroupName, siteName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-104">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-104">Name of the app.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-105">Deaktivieren Sie alle Empfehlungen für eine app an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-105">Disable all recommendations for an app.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5d0aa-106">Deaktivieren Sie alle Empfehlungen für eine app an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-106">Disable all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAllForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableAllForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableAllForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;DisableAllForWebAppAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-108">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-108">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-109">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-109">Name of the app.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d0aa-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-111">Deaktivieren Sie alle Empfehlungen für eine app an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-111">Disable all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-112">Deaktivieren Sie alle Empfehlungen für eine app an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-112">Disable all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebApp">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.RecommendationRule GetRuleDetailsByWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.RecommendationRule GetRuleDetailsByWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRuleDetailsByWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, name As String, Optional updateSeen As Nullable(Of Boolean) = null) As RecommendationRule" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.RecommendationRule" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebApp (operations, resourceGroupName, siteName, name, updateSeen)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.RecommendationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-114">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-114">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-115">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-115">Name of the app.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5d0aa-116">Der Name der Empfehlung.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-116">Name of the recommendation.</span></span>
            </param>
        <param name="updateSeen">
            <span data-ttu-id="5d0aa-117">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den letzten gesehen Zeitstempel des Objekts Empfehlung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-117">Specify &lt;code&gt;true&lt;/code&gt; to update the last-seen timestamp of the recommendation object.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-118">Eine Regel für die Empfehlung für eine app abrufen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-118">Get a recommendation rule for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-119">Eine Regel für die Empfehlung für eine app abrufen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-119">Get a recommendation rule for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt; GetRuleDetailsByWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt; GetRuleDetailsByWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync (operations, resourceGroupName, siteName, name, updateSeen, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;GetRuleDetailsByWebAppAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-121">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-121">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-122">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-122">Name of the app.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5d0aa-123">Der Name der Empfehlung.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-123">Name of the recommendation.</span></span>
            </param>
        <param name="updateSeen">
            <span data-ttu-id="5d0aa-124">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den letzten gesehen Zeitstempel des Objekts Empfehlung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-124">Specify &lt;code&gt;true&lt;/code&gt; to update the last-seen timestamp of the recommendation object.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d0aa-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-126">Eine Regel für die Empfehlung für eine app abrufen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-126">Get a recommendation rule for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-127">Eine Regel für die Empfehlung für eine app abrufen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-127">Get a recommendation rule for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; List (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; List(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRecommendationsOperations, Optional featured As Nullable(Of Boolean) = null, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * Nullable&lt;bool&gt; * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.List (operations, featured, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-128">The operations group for this extension method.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="5d0aa-129">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-129">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="5d0aa-130">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-130">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="5d0aa-131">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-131">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="5d0aa-132">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]</span><span class="sxs-lookup"><span data-stu-id="5d0aa-132">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-133">Liste aller Empfehlungen für ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-133">List all recommendations for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-134">Liste aller Empfehlungen für ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-134">List all recommendations for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListAsync (operations, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-135">The operations group for this extension method.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="5d0aa-136">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-136">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="5d0aa-137">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-137">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="5d0aa-138">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-138">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="5d0aa-139">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]</span><span class="sxs-lookup"><span data-stu-id="5d0aa-139">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d0aa-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-141">Liste aller Empfehlungen für ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-141">List all recommendations for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-142">Liste aller Empfehlungen für ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-142">List all recommendations for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebApp">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListHistoryForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListHistoryForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHistoryForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebApp (operations, resourceGroupName, siteName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-144">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-145">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-145">Name of the app.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="5d0aa-146">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-146">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="5d0aa-147">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]</span><span class="sxs-lookup"><span data-stu-id="5d0aa-147">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-148">Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-148">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-149">Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-149">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListHistoryForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListHistoryForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync (operations, resourceGroupName, siteName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListHistoryForWebAppAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-151">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-152">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-152">Name of the app.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="5d0aa-153">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-153">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="5d0aa-154">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]</span><span class="sxs-lookup"><span data-stu-id="5d0aa-154">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d0aa-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-156">Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-156">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-157">Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-157">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebApp">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListRecommendedRulesForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListRecommendedRulesForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRecommendedRulesForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, Optional featured As Nullable(Of Boolean) = null, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebApp (operations, resourceGroupName, siteName, featured, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-159">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-160">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-160">Name of the app.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="5d0aa-161">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-161">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="5d0aa-162">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-162">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="5d0aa-163">Geben Sie nur die Kanäle, die im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-163">Return only channels specified in the filter.</span></span> <span data-ttu-id="5d0aa-164">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-164">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="5d0aa-165">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung"</span><span class="sxs-lookup"><span data-stu-id="5d0aa-165">Example: $filter=channels eq 'Api' or channel eq 'Notification'</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-166">Rufen Sie aller Empfehlungen für eine app an ab.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-166">Get all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-167">Rufen Sie aller Empfehlungen für eine app an ab.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-167">Get all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListRecommendedRulesForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListRecommendedRulesForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync (operations, resourceGroupName, siteName, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListRecommendedRulesForWebAppAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-169">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-169">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-170">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-170">Name of the app.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="5d0aa-171">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-171">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="5d0aa-172">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-172">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="5d0aa-173">Geben Sie nur die Kanäle, die im Filter angegebenen zurück.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-173">Return only channels specified in the filter.</span></span> <span data-ttu-id="5d0aa-174">Filter wird mithilfe von OData-Syntax angegeben.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-174">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="5d0aa-175">Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung"</span><span class="sxs-lookup"><span data-stu-id="5d0aa-175">Example: $filter=channels eq 'Api' or channel eq 'Notification'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d0aa-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-177">Rufen Sie aller Empfehlungen für eine app an ab.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-177">Get all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-178">Rufen Sie aller Empfehlungen für eine app an ab.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-178">Get all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFilters">
      <MemberSignature Language="C#" Value="public static void ResetAllFilters (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResetAllFilters(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFilters(Microsoft.Azure.Management.WebSites.IRecommendationsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ResetAllFilters (operations As IRecommendationsOperations)" />
      <MemberSignature Language="F#" Value="static member ResetAllFilters : Microsoft.Azure.Management.WebSites.IRecommendationsOperations -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFilters operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-179">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-180">Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-180">Reset all recommendation opt-out settings for a subscription.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5d0aa-181">Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-181">Reset all recommendation opt-out settings for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ResetAllFiltersAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-182">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d0aa-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-184">Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-184">Reset all recommendation opt-out settings for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-185">Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-185">Reset all recommendation opt-out settings for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebApp">
      <MemberSignature Language="C#" Value="public static void ResetAllFiltersForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResetAllFiltersForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ResetAllFiltersForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebApp (operations, resourceGroupName, siteName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-187">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-188">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-188">Name of the app.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-189">Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-189">Reset all recommendation opt-out settings for an app.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5d0aa-190">Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-190">Reset all recommendation opt-out settings for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ResetAllFiltersForWebAppAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d0aa-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d0aa-192">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-192">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="5d0aa-193">Der Name der app.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-193">Name of the app.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d0aa-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d0aa-195">Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-195">Reset all recommendation opt-out settings for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5d0aa-196">Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="5d0aa-196">Reset all recommendation opt-out settings for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>