<Type Name="SubscriptionUsagesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionUsagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionUsagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionUsagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionUsagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="541f9-101">Erweiterungsmethoden für SubscriptionUsagesOperations.</span><span class="sxs-lookup"><span data-stu-id="541f9-101">Extension methods for SubscriptionUsagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SubscriptionUsage Get (this Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName, string usageName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SubscriptionUsage Get(class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName, string usageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubscriptionUsagesOperations, locationName As String, usageName As String) As SubscriptionUsage" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SubscriptionUsage" Usage="Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.Get (operations, locationName, usageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SubscriptionUsage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="usageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="541f9-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="541f9-102">The operations group for this extension method.</span></span>
            </param>
        <param name="locationName">
            <span data-ttu-id="541f9-103">Der Name der Region, in dem die Ressource befindet.</span><span class="sxs-lookup"><span data-stu-id="541f9-103">The name of the region where the resource is located.</span></span>
            </param>
        <param name="usageName">
            <span data-ttu-id="541f9-104">Der Name der Nutzung Metrik zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="541f9-104">Name of usage metric to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="541f9-105">Ruft die Metrik ein Abonnement Verwendung ab.</span><span class="sxs-lookup"><span data-stu-id="541f9-105">Gets a subscription usage metric.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt; GetAsync (this Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName, string usageName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt; GetAsync(class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName, string usageName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;" Usage="Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.GetAsync (operations, locationName, usageName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="usageName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="541f9-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="541f9-106">The operations group for this extension method.</span></span>
            </param>
        <param name="locationName">
            <span data-ttu-id="541f9-107">Der Name der Region, in dem die Ressource befindet.</span><span class="sxs-lookup"><span data-stu-id="541f9-107">The name of the region where the resource is located.</span></span>
            </param>
        <param name="usageName">
            <span data-ttu-id="541f9-108">Der Name der Nutzung Metrik zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="541f9-108">Name of usage metric to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="541f9-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="541f9-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="541f9-110">Ruft die Metrik ein Abonnement Verwendung ab.</span><span class="sxs-lookup"><span data-stu-id="541f9-110">Gets a subscription usage metric.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByLocation">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt; ListByLocation (this Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt; ListByLocation(class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocation(Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByLocation (operations As ISubscriptionUsagesOperations, locationName As String) As IPage(Of SubscriptionUsage)" />
      <MemberSignature Language="F#" Value="static member ListByLocation : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;" Usage="Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocation (operations, locationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="541f9-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="541f9-111">The operations group for this extension method.</span></span>
            </param>
        <param name="locationName">
            <span data-ttu-id="541f9-112">Der Name der Region, in dem die Ressource befindet.</span><span class="sxs-lookup"><span data-stu-id="541f9-112">The name of the region where the resource is located.</span></span>
            </param>
        <summary>
            <span data-ttu-id="541f9-113">Ruft die nutzungsmetriken für alle Abonnements in einem angegebenen Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="541f9-113">Gets all subscription usage metrics in a given location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByLocationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt; ListByLocationAsync (this Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt; ListByLocationAsync(class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string locationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocationAsync(Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByLocationAsync : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocationAsync (operations, locationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions/&lt;ListByLocationAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="541f9-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="541f9-114">The operations group for this extension method.</span></span>
            </param>
        <param name="locationName">
            <span data-ttu-id="541f9-115">Der Name der Region, in dem die Ressource befindet.</span><span class="sxs-lookup"><span data-stu-id="541f9-115">The name of the region where the resource is located.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="541f9-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="541f9-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="541f9-117">Ruft die nutzungsmetriken für alle Abonnements in einem angegebenen Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="541f9-117">Gets all subscription usage metrics in a given location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByLocationNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt; ListByLocationNext (this Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt; ListByLocationNext(class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocationNext(Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByLocationNext (operations As ISubscriptionUsagesOperations, nextPageLink As String) As IPage(Of SubscriptionUsage)" />
      <MemberSignature Language="F#" Value="static member ListByLocationNext : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;" Usage="Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocationNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="541f9-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="541f9-118">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="541f9-119">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="541f9-119">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="541f9-120">Ruft die nutzungsmetriken für alle Abonnements in einem angegebenen Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="541f9-120">Gets all subscription usage metrics in a given location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByLocationNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt; ListByLocationNextAsync (this Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt; ListByLocationNextAsync(class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocationNextAsync(Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByLocationNextAsync : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions.ListByLocationNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SubscriptionUsagesOperationsExtensions/&lt;ListByLocationNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SubscriptionUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="541f9-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="541f9-121">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="541f9-122">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="541f9-122">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="541f9-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="541f9-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="541f9-124">Ruft die nutzungsmetriken für alle Abonnements in einem angegebenen Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="541f9-124">Gets all subscription usage metrics in a given location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>