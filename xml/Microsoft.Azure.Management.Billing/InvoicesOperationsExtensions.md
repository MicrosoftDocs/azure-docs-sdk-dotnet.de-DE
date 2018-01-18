<Type Name="InvoicesOperationsExtensions" FullName="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InvoicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InvoicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InvoicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InvoicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1b5f-101">Erweiterungsmethoden für InvoicesOperations.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-101">Extension methods for InvoicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Billing.Models.Invoice Get (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Billing.Models.Invoice Get(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.Get(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInvoicesOperations, invoiceName As String) As Invoice" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Billing.IInvoicesOperations * string -&gt; Microsoft.Azure.Management.Billing.Models.Invoice" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.Get (operations, invoiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.Invoice</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="invoiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="invoiceName">
            <span data-ttu-id="d1b5f-103">Der Name einer Ressource Rechnung.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-103">The name of an invoice resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-104">Ruft eine benannte Rechnung-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-104">Gets a named invoice resource.</span></span> <span data-ttu-id="d1b5f-105">Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-105">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetAsync (operations, invoiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="invoiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-106">The operations group for this extension method.</span></span>
            </param>
        <param name="invoiceName">
            <span data-ttu-id="d1b5f-107">Der Name einer Ressource Rechnung.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-107">The name of an invoice resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1b5f-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-109">Ruft eine benannte Rechnung-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-109">Gets a named invoice resource.</span></span> <span data-ttu-id="d1b5f-110">Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-110">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLatest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Billing.Models.Invoice GetLatest (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Billing.Models.Invoice GetLatest(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatest(Microsoft.Azure.Management.Billing.IInvoicesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLatest (operations As IInvoicesOperations) As Invoice" />
      <MemberSignature Language="F#" Value="static member GetLatest : Microsoft.Azure.Management.Billing.IInvoicesOperations -&gt; Microsoft.Azure.Management.Billing.Models.Invoice" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatest operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.Invoice</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-111">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-112">Ruft die letzten Rechnung ab.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-112">Gets the most recent invoice.</span></span> <span data-ttu-id="d1b5f-113">Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-113">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLatestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetLatestAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetLatestAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatestAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetLatestAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;GetLatestAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-114">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1b5f-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-116">Ruft die letzten Rechnung ab.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-116">Gets the most recent invoice.</span></span> <span data-ttu-id="d1b5f-117">Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-117">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; List (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; List(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.List(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IInvoicesOperations, Optional expand As String = null, Optional filter As String = null, Optional skiptoken As String = null, Optional top As Nullable(Of Integer) = null) As IPage(Of Invoice)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.List (operations, expand, filter, skiptoken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-118">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="d1b5f-119">Kann verwendet werden, um die DownloadUrl-Eigenschaft in einer Liste von Rechnungen zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-119">May be used to expand the downloadUrl property within a list of invoices.</span></span>
            <span data-ttu-id="d1b5f-120">Dies ermöglicht Downloadlinks gleichzeitig für mehrere Rechnungen generiert werden.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-120">This enables download links to be generated for multiple invoices at once.</span></span>
            <span data-ttu-id="d1b5f-121">Standardmäßig sind DownloadURLs beim Auflisten von Rechnungen nicht enthalten.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-121">By default, downloadURLs are not included when listing invoices.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="d1b5f-122">Kann verwendet werden, Rechnungen Filtern von InvoicePeriodEndDate.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-122">May be used to filter invoices by invoicePeriodEndDate.</span></span> <span data-ttu-id="d1b5f-123">Der Filter unterstützt "Eq", "Lt", 'Gt', 'le', "ge", und "und".</span><span class="sxs-lookup"><span data-stu-id="d1b5f-123">The filter supports 'eq', 'lt', 'gt', 'le', 'ge', and 'and'.</span></span> <span data-ttu-id="d1b5f-124">Es derzeit nicht unterstützt 'Ne', 'oder' oder 'nicht'.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-124">It does not currently support 'ne', 'or', or 'not'.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="d1b5f-125">Skiptoken wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-125">Skiptoken is only used if a previous operation returned a partial result.</span></span>
            <span data-ttu-id="d1b5f-126">Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen Skiptoken-Parameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-126">If a previous response contains a nextLink element, the value of the nextLink element will include a skiptoken parameter that specifies a starting point to use for subsequent calls.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="d1b5f-127">Kann verwendet werden, um die Anzahl der Ergebnisse in den letzten N Rechnungen zu beschränken.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-127">May be used to limit the number of results to the most recent N invoices.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-128">Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-128">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="d1b5f-129">In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-129">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListAsync (operations, expand, filter, skiptoken, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-130">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="d1b5f-131">Kann verwendet werden, um die DownloadUrl-Eigenschaft in einer Liste von Rechnungen zu erweitern.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-131">May be used to expand the downloadUrl property within a list of invoices.</span></span>
            <span data-ttu-id="d1b5f-132">Dies ermöglicht Downloadlinks gleichzeitig für mehrere Rechnungen generiert werden.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-132">This enables download links to be generated for multiple invoices at once.</span></span>
            <span data-ttu-id="d1b5f-133">Standardmäßig sind DownloadURLs beim Auflisten von Rechnungen nicht enthalten.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-133">By default, downloadURLs are not included when listing invoices.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="d1b5f-134">Kann verwendet werden, Rechnungen Filtern von InvoicePeriodEndDate.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-134">May be used to filter invoices by invoicePeriodEndDate.</span></span> <span data-ttu-id="d1b5f-135">Der Filter unterstützt "Eq", "Lt", 'Gt', 'le', "ge", und "und".</span><span class="sxs-lookup"><span data-stu-id="d1b5f-135">The filter supports 'eq', 'lt', 'gt', 'le', 'ge', and 'and'.</span></span> <span data-ttu-id="d1b5f-136">Es derzeit nicht unterstützt 'Ne', 'oder' oder 'nicht'.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-136">It does not currently support 'ne', 'or', or 'not'.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="d1b5f-137">Skiptoken wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-137">Skiptoken is only used if a previous operation returned a partial result.</span></span>
            <span data-ttu-id="d1b5f-138">Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen Skiptoken-Parameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-138">If a previous response contains a nextLink element, the value of the nextLink element will include a skiptoken parameter that specifies a starting point to use for subsequent calls.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="d1b5f-139">Kann verwendet werden, um die Anzahl der Ergebnisse in den letzten N Rechnungen zu beschränken.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-139">May be used to limit the number of results to the most recent N invoices.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1b5f-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-141">Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-141">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="d1b5f-142">In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-142">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; ListNext (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; ListNext(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNext(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IInvoicesOperations, nextPageLink As String) As IPage(Of Invoice)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Billing.IInvoicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-143">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d1b5f-144">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-144">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-145">Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-145">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="d1b5f-146">In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-146">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d1b5f-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-147">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d1b5f-148">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-148">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1b5f-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1b5f-150">Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-150">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="d1b5f-151">In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.</span><span class="sxs-lookup"><span data-stu-id="d1b5f-151">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>