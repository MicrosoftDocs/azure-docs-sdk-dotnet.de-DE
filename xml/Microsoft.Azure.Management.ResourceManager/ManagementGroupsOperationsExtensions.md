<Type Name="ManagementGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ManagementGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ManagementGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ManagementGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ManagementGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="6e3f9-101">Erweiterungsmethoden für ManagementGroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-101">Extension methods for ManagementGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy Get (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand = null, Nullable&lt;bool&gt; recurse = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy Get(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand, valuetype System.Nullable`1&lt;bool&gt; recurse) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IManagementGroupsOperations, Optional expand As String = null, Optional recurse As Nullable(Of Boolean) = null) As ManagementGroupWithHierarchy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.Get (operations, expand, recurse)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="recurse" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="6e3f9-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-102">The operations group for this extension method.</span></span>
             </param>
        <param name="expand">
             <span data-ttu-id="6e3f9-103">Die $expand-= untergeordnetes Element Abfragezeichenfolgen-Parameter Clients Anforderung Aufnahme der untergeordneten Elemente in der antwortnutzlast kann.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-103">The $expand=children query string parameter allows clients to request inclusion of children in the response payload.</span></span> <span data-ttu-id="6e3f9-104">Folgende Werte sind möglich: "untergeordnete Elemente"</span><span class="sxs-lookup"><span data-stu-id="6e3f9-104">Possible values include: 'children'</span></span>
             </param>
        <param name="recurse">
             <span data-ttu-id="6e3f9-105">Die $recurse = "true" Abfrage Zeichenfolgenparameter ermöglicht Clients die Einbindung der gesamten Hierarchie in der antwortnutzlast anfordern.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-105">The $recurse=true query string parameter allows clients to request inclusion of entire hierarchy in the response payload.</span></span>
             </param>
        <summary>
             <span data-ttu-id="6e3f9-106">Abrufen von Details der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-106">Get the details of the management group.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand = null, Nullable&lt;bool&gt; recurse = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand, valuetype System.Nullable`1&lt;bool&gt; recurse, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.GetAsync (operations, expand, recurse, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="recurse" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="6e3f9-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-107">The operations group for this extension method.</span></span>
             </param>
        <param name="expand">
             <span data-ttu-id="6e3f9-108">Die $expand-= untergeordnetes Element Abfragezeichenfolgen-Parameter Clients Anforderung Aufnahme der untergeordneten Elemente in der antwortnutzlast kann.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-108">The $expand=children query string parameter allows clients to request inclusion of children in the response payload.</span></span> <span data-ttu-id="6e3f9-109">Folgende Werte sind möglich: "untergeordnete Elemente"</span><span class="sxs-lookup"><span data-stu-id="6e3f9-109">Possible values include: 'children'</span></span>
             </param>
        <param name="recurse">
             <span data-ttu-id="6e3f9-110">Die $recurse = "true" Abfrage Zeichenfolgenparameter ermöglicht Clients die Einbindung der gesamten Hierarchie in der antwortnutzlast anfordern.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-110">The $recurse=true query string parameter allows clients to request inclusion of entire hierarchy in the response payload.</span></span>
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="6e3f9-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-111">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="6e3f9-112">Abrufen von Details der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-112">Get the details of the management group.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; List (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; List(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IManagementGroupsOperations, Optional skiptoken As String = null) As IPage(Of ManagementGroupInfo)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.List (operations, skiptoken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="skiptoken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="6e3f9-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-113">The operations group for this extension method.</span></span>
             </param>
        <param name="skiptoken">
             <span data-ttu-id="6e3f9-114">Fortsetzungstoken für die Seite wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-114">Page continuation token is only used if a previous operation returned a partial result.</span></span>
             <span data-ttu-id="6e3f9-115">Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen tokenparameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-115">If a previous response contains a nextLink element, the value of the nextLink element will include a token parameter that specifies a starting point to use for subsequent calls.</span></span>
             
             </param>
        <summary>
             <span data-ttu-id="6e3f9-116">Liste der Verwaltungsgruppen für den authentifizierten Benutzer.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-116">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListAsync (operations, skiptoken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="6e3f9-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-117">The operations group for this extension method.</span></span>
             </param>
        <param name="skiptoken">
             <span data-ttu-id="6e3f9-118">Fortsetzungstoken für die Seite wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-118">Page continuation token is only used if a previous operation returned a partial result.</span></span>
             <span data-ttu-id="6e3f9-119">Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen tokenparameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-119">If a previous response contains a nextLink element, the value of the nextLink element will include a token parameter that specifies a starting point to use for subsequent calls.</span></span>
             
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="6e3f9-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-120">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="6e3f9-121">Liste der Verwaltungsgruppen für den authentifizierten Benutzer.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-121">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IManagementGroupsOperations, nextPageLink As String) As IPage(Of ManagementGroupInfo)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="6e3f9-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-122">The operations group for this extension method.</span></span>
             </param>
        <param name="nextPageLink">
             <span data-ttu-id="6e3f9-123">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-123">The NextLink from the previous successful call to List operation.</span></span>
             </param>
        <summary>
             <span data-ttu-id="6e3f9-124">Liste der Verwaltungsgruppen für den authentifizierten Benutzer.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-124">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="6e3f9-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-125">The operations group for this extension method.</span></span>
             </param>
        <param name="nextPageLink">
             <span data-ttu-id="6e3f9-126">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-126">The NextLink from the previous successful call to List operation.</span></span>
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="6e3f9-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-127">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="6e3f9-128">Liste der Verwaltungsgruppen für den authentifizierten Benutzer.</span><span class="sxs-lookup"><span data-stu-id="6e3f9-128">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>