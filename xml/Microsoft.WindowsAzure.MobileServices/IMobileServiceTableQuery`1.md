<Type Name="IMobileServiceTableQuery&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IMobileServiceTableQuery&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceTableQuery`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceTableQuery(Of T)" />
  <TypeSignature Language="F#" Value="type IMobileServiceTableQuery&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="5731a-101">Stellt eine Abfrage, die anhand einer Mobile Services-Tabelle ausgewertet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5731a-101">Represents a query that can be evaluated against a Mobile Services table.</span></span> <span data-ttu-id="5731a-102">MobileServiceTableQuery-Instanzen können über MobileServiceClient.Query (of T)(). abgerufen werden</span><span class="sxs-lookup"><span data-stu-id="5731a-102">MobileServiceTableQuery instances can be obtained via MobileServiceClient.Query(of T)().</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="5731a-103">Anstatt implementieren IQueryable ist direkt haben wir den Teil des LINQ-Abfragemusters implementiert, der für MobileServiceTableQuery-Objekte unterstützt.</span><span class="sxs-lookup"><span data-stu-id="5731a-103">Rather than implenting IQueryable directly, we've implemented the portion of the LINQ query pattern we support on MobileServiceTableQuery objects.</span></span>  <span data-ttu-id="5731a-104">MobileServiceTableQuery-Instanzen werden verwendet, um iqueryables von LINQ-Abfragevorgänge zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5731a-104">MobileServiceTableQuery instances are used to build up IQueryables from LINQ query operations.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="IncludeDeleted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeDeleted ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeDeleted() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.IncludeDeleted" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeDeleted () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeDeleted : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.IncludeDeleted " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5731a-105">Stellen Sie sicher, dass die Abfrage die gelöschten Datensätze abruft.</span><span class="sxs-lookup"><span data-stu-id="5731a-105">Ensure the query will get the deleted records.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-106">Das Abfrageobjekt.</span><span class="sxs-lookup"><span data-stu-id="5731a-106">The query object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalCount">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeTotalCount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeTotalCount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.IncludeTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeTotalCount () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeTotalCount : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.IncludeTotalCount " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5731a-107">Stellt sicher, dass die Abfrage die Gesamtanzahl für alle Datensätze abruft, die ohne jegliche vom Client oder Server angegebene Paging-/Limit-Klausel zurückgegeben worden wäre.</span><span class="sxs-lookup"><span data-stu-id="5731a-107">Ensure the query will get the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-108">Das Abfrageobjekt.</span><span class="sxs-lookup"><span data-stu-id="5731a-108">The query object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.OrderBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.OrderBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="5731a-109">Der Typ des Members, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-109">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5731a-110">Der Ausdruck, der den Member auswählt, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-110">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-111">Wendet die angegebene Order-Klausel für eine aufsteigende Sortierreihenfolge auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-111">Applies the specified ascending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-112">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-112">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.OrderByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.OrderByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="5731a-113">Der Typ des Members, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-113">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5731a-114">Der Ausdruck, der den Member auswählt, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-114">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-115">Wendet die angegebene Order-Klausel für eine absteigende Sortierreihenfolge auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-115">Applies the specified descending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-116">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-116">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5731a-117">Die benutzerdefinierten Abfragezeichenfolgenparameter für die Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-117">The user-defined query string parameters to include with the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.IQueryable`1&lt;!T&gt; Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As IQueryable(Of T)" />
      <MemberSignature Language="F#" Value="member this.Query : System.Linq.IQueryable&lt;'T&gt; with get, set" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5731a-118">Ruft das zugrunde liegende IQueryable-Objekt mit dieser Abfrage verbunden.</span><span class="sxs-lookup"><span data-stu-id="5731a-118">Gets the underlying IQueryable associated with this query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTotalCount">
      <MemberSignature Language="C#" Value="public bool RequestTotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequestTotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.RequestTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestTotalCount As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequestTotalCount : bool" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.RequestTotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5731a-119">Ruft einen Wert, der angibt, ob die Abfrage die Gesamtanzahl für alle Datensätze anfordert, die zurückgegeben worden wären wird vom Client oder Server angegebenen Take Paging/Limit-Klausel ignoriert.</span><span class="sxs-lookup"><span data-stu-id="5731a-119">Gets a value indicating whether the query will request the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select&lt;U&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; Select&lt;U&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,U&gt;&gt; selector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; Select&lt;U&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!U&gt;&gt; selector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Select``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select(Of U) (selector As Expression(Of Func(Of T, U))) As IMobileServiceTableQuery(Of U)" />
      <MemberSignature Language="F#" Value="abstract member Select : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'U&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt;" Usage="iMobileServiceTableQuery.Select selector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="selector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,U&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="U">
            <span data-ttu-id="5731a-120">Der Typ, der das projizierte Ergebnis der Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="5731a-120">Type representing the projected result of the query.</span></span>
            </typeparam>
        <param name="selector">
            <span data-ttu-id="5731a-121">Die Auswahlfunktion.</span><span class="sxs-lookup"><span data-stu-id="5731a-121">The selector function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-122">Wendet die angegebene Auswahl auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-122">Applies the specified selection to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-123">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-123">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Skip (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Skip(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Skip(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Skip (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Skip : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.Skip count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            <span data-ttu-id="5731a-124">Die zu überspringende Zahl.</span><span class="sxs-lookup"><span data-stu-id="5731a-124">The number to skip.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-125">Wendet die angegebene Skip-Klausel auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-125">Applies the specified skip clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-126">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-126">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt; Table { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1&lt;!T&gt; Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Table" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Table As IMobileServiceTable(Of T)" />
      <MemberSignature Language="F#" Value="member this.Table : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'T&gt;" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5731a-127">Ruft die abgefragte MobileServiceTable ab.</span><span class="sxs-lookup"><span data-stu-id="5731a-127">Gets the MobileServiceTable being queried.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Take (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Take(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Take(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Take : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.Take count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            <span data-ttu-id="5731a-128">Die zu erfassende Zahl.</span><span class="sxs-lookup"><span data-stu-id="5731a-128">The number to take.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-129">Wendet die angegebene Take-Klausel auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-129">Applies the specified take clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-130">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-130">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ThenBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.ThenBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="5731a-131">Der Typ des Members, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-131">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5731a-132">Der Ausdruck, der den Member auswählt, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-132">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-133">Wendet die angegebene Order-Klausel für eine aufsteigende Sortierreihenfolge auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-133">Applies the specified ascending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-134">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-134">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ThenByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.ThenByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="5731a-135">Der Typ des Members, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-135">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5731a-136">Der Ausdruck, der den Member auswählt, nach dem sortiert wird.</span><span class="sxs-lookup"><span data-stu-id="5731a-136">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-137">Wendet die angegebene Order-Klausel für eine absteigende Sortierreihenfolge auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-137">Applies the specified descending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-138">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-138">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ToEnumerableAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ToEnumerableAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ToEnumerableAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerableAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToEnumerableAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceTableQuery.ToEnumerableAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5731a-139">Asynchrones Auswerten der Abfrage asynchron und die Ergebnisse zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="5731a-139">Evalute the query asynchronously and return the results.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-140">Die ausgewerteten Abfrageergebnisse.</span><span class="sxs-lookup"><span data-stu-id="5731a-140">The evaluated query results.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!T&gt;&gt; ToListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ToListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToListAsync () As Task(Of List(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="iMobileServiceTableQuery.ToListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5731a-141">Asynchrones Auswerten der Abfrage asynchron und Zurückgeben der Ergebnisse in eine neue Liste.</span><span class="sxs-lookup"><span data-stu-id="5731a-141">Evalute the query asynchronously and return the results in a new List.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-142">Die ausgewerteten Abfrageergebnisse als Liste.</span><span class="sxs-lookup"><span data-stu-id="5731a-142">The evaluated query results as a List.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Where (System.Linq.Expressions.Expression&lt;Func&lt;T,bool&gt;&gt; predicate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Where(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, bool&gt;&gt; predicate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Where(System.Linq.Expressions.Expression{System.Func{`0,System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (predicate As Expression(Of Func(Of T, Boolean))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Where : System.Linq.Expressions.Expression&lt;Func&lt;'T, bool&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.Where predicate" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="predicate" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="predicate">
            <span data-ttu-id="5731a-143">Das Filterprädikat.</span><span class="sxs-lookup"><span data-stu-id="5731a-143">The filter predicate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-144">Wendet das angegebene Filterprädikat auf die Quellabfrage an.</span><span class="sxs-lookup"><span data-stu-id="5731a-144">Applies the specified filter predicate to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-145">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-145">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; WithParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; WithParameters(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.WithParameters(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parameters As IDictionary(Of String, String)) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.WithParameters parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="5731a-146">Die anzuwendenden Parameter.</span><span class="sxs-lookup"><span data-stu-id="5731a-146">The parameters to apply.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5731a-147">Gilt für die Quellabfrage angegebene Zeichenfolge Schlüssel-Wert-Paare als benutzerdefinierte Parameter mit der Anforderungs-URI-Abfragezeichenfolge verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5731a-147">Applies to the source query the specified string key-value pairs to be used as user-defined parameters with the request URI query string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5731a-148">Die zusammengesetzte Abfrage.</span><span class="sxs-lookup"><span data-stu-id="5731a-148">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>