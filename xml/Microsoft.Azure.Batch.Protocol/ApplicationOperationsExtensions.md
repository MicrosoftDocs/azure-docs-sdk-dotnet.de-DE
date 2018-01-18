<Type Name="ApplicationOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="312af-101">Erweiterungsmethoden für ApplicationOperations.</span><span class="sxs-lookup"><span data-stu-id="312af-101">Extension methods for ApplicationOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary Get (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary Get(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.Get (operations, applicationId, applicationGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="applicationGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="312af-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="312af-102">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="312af-103">Die ID der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="312af-103">The ID of the application.</span></span>
            </param>
        <param name="applicationGetOptions">
            <span data-ttu-id="312af-104">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="312af-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="312af-105">Ruft Informationen über die angegebene Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="312af-105">Gets information about the specified application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="312af-106">Dieser Vorgang gibt nur die Anwendungen und Versionen, die für die Verwendung in der Compute-Knoten verfügbar sind; d. h., die in einem Paket Anwendungsverweis verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="312af-106">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="312af-107">Verwenden Sie für die Administratorinformationen zu Anwendungen und Versionen, die noch nicht für die Serverknoten verfügbar sind, Azure-Portal oder die API der Azure-Ressourcen-Manager aus.</span><span class="sxs-lookup"><span data-stu-id="312af-107">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string applicationId, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.GetAsync (operations, applicationId, applicationGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="applicationGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="312af-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="312af-108">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="312af-109">Die ID der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="312af-109">The ID of the application.</span></span>
            </param>
        <param name="applicationGetOptions">
            <span data-ttu-id="312af-110">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="312af-110">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="312af-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="312af-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="312af-112">Ruft Informationen über die angegebene Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="312af-112">Gets information about the specified application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="312af-113">Dieser Vorgang gibt nur die Anwendungen und Versionen, die für die Verwendung in der Compute-Knoten verfügbar sind; d. h., die in einem Paket Anwendungsverweis verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="312af-113">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="312af-114">Verwenden Sie für die Administratorinformationen zu Anwendungen und Versionen, die noch nicht für die Serverknoten verfügbar sind, Azure-Portal oder die API der Azure-Ressourcen-Manager aus.</span><span class="sxs-lookup"><span data-stu-id="312af-114">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; List (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; List(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IApplicationOperations,Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IApplicationOperations * Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.List (operations, applicationListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="312af-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="312af-115">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationListOptions">
            <span data-ttu-id="312af-116">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="312af-116">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="312af-117">Zeigt eine Liste aller Anwendungen in das angegebene Konto verfügbar.</span><span class="sxs-lookup"><span data-stu-id="312af-117">Lists all of the applications available in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="312af-118">Dieser Vorgang gibt nur die Anwendungen und Versionen, die für die Verwendung in der Compute-Knoten verfügbar sind; d. h., die in einem Paket Anwendungsverweis verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="312af-118">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="312af-119">Verwenden Sie für die Administratorinformationen zu Anwendungen und Versionen, die noch nicht für die Serverknoten verfügbar sind, Azure-Portal oder die API der Azure-Ressourcen-Manager aus.</span><span class="sxs-lookup"><span data-stu-id="312af-119">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IApplicationOperations,Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IApplicationOperations * Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListAsync (operations, applicationListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="applicationListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="312af-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="312af-120">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationListOptions">
            <span data-ttu-id="312af-121">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="312af-121">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="312af-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="312af-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="312af-123">Zeigt eine Liste aller Anwendungen in das angegebene Konto verfügbar.</span><span class="sxs-lookup"><span data-stu-id="312af-123">Lists all of the applications available in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="312af-124">Dieser Vorgang gibt nur die Anwendungen und Versionen, die für die Verwendung in der Compute-Knoten verfügbar sind; d. h., die in einem Paket Anwendungsverweis verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="312af-124">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="312af-125">Verwenden Sie für die Administratorinformationen zu Anwendungen und Versionen, die noch nicht für die Serverknoten verfügbar sind, Azure-Portal oder die API der Azure-Ressourcen-Manager aus.</span><span class="sxs-lookup"><span data-stu-id="312af-125">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNext (operations, nextPageLink, applicationListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="applicationListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="312af-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="312af-126">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="312af-127">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="312af-127">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="applicationListNextOptions">
            <span data-ttu-id="312af-128">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="312af-128">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="312af-129">Zeigt eine Liste aller Anwendungen in das angegebene Konto verfügbar.</span><span class="sxs-lookup"><span data-stu-id="312af-129">Lists all of the applications available in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="312af-130">Dieser Vorgang gibt nur die Anwendungen und Versionen, die für die Verwendung in der Compute-Knoten verfügbar sind; d. h., die in einem Paket Anwendungsverweis verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="312af-130">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="312af-131">Verwenden Sie für die Administratorinformationen zu Anwendungen und Versionen, die noch nicht für die Serverknoten verfügbar sind, Azure-Portal oder die API der Azure-Ressourcen-Manager aus.</span><span class="sxs-lookup"><span data-stu-id="312af-131">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IApplicationOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IApplicationOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IApplicationOperations * string * Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions.ListNextAsync (operations, nextPageLink, applicationListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ApplicationOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IApplicationOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="applicationListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="312af-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="312af-132">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="312af-133">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="312af-133">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="applicationListNextOptions">
            <span data-ttu-id="312af-134">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="312af-134">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="312af-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="312af-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="312af-136">Zeigt eine Liste aller Anwendungen in das angegebene Konto verfügbar.</span><span class="sxs-lookup"><span data-stu-id="312af-136">Lists all of the applications available in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="312af-137">Dieser Vorgang gibt nur die Anwendungen und Versionen, die für die Verwendung in der Compute-Knoten verfügbar sind; d. h., die in einem Paket Anwendungsverweis verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="312af-137">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="312af-138">Verwenden Sie für die Administratorinformationen zu Anwendungen und Versionen, die noch nicht für die Serverknoten verfügbar sind, Azure-Portal oder die API der Azure-Ressourcen-Manager aus.</span><span class="sxs-lookup"><span data-stu-id="312af-138">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>