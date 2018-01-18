<Type Name="MobileServiceCollection&lt;TTable,TCollection&gt;" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TCollection&gt;">
  <TypeSignature Language="C#" Value="public class MobileServiceCollection&lt;TTable,TCollection&gt; : System.Collections.ObjectModel.ObservableCollection&lt;TCollection&gt;, Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;TCollection&gt;, Microsoft.WindowsAzure.MobileServices.ITotalCountProvider, System.Collections.Generic.IEnumerable&lt;TCollection&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceCollection`2&lt;TTable, TCollection&gt; extends System.Collections.ObjectModel.ObservableCollection`1&lt;!TCollection&gt; implements class Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1&lt;!TCollection&gt;, class Microsoft.WindowsAzure.MobileServices.ITotalCountProvider, class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceCollection(Of TTable, TCollection)&#xA;Inherits ObservableCollection(Of TCollection)&#xA;Implements IEnumerable(Of TCollection), IQueryResultEnumerable(Of TCollection), ITotalCountProvider" />
  <TypeSignature Language="F#" Value="type MobileServiceCollection&lt;'able, 'Collection&gt; = class&#xA;    inherit ObservableCollection&lt;'Collection&gt;&#xA;    interface ITotalCountProvider&#xA;    interface IQueryResultEnumerable&lt;'Collection&gt;&#xA;    interface seq&lt;'Collection&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TTable" />
    <TypeParameter Name="TCollection" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.ObservableCollection&lt;TCollection&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">TCollection</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;TCollection&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.ITotalCountProvider</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;TCollection&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TTable"><span data-ttu-id="4dd3b-101">Datenquellen-Elementtyp.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-101">Data source element type.</span></span></typeparam>
    <typeparam name="TCollection"><span data-ttu-id="4dd3b-102">Der Typ der Elemente in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-102">Type of elements ending up in the collection.</span></span></typeparam>
    <summary>
            <span data-ttu-id="4dd3b-103">Eine asynchrone Datenquelle, die die Ergebnisse einer Mobile Services-Abfrage so einfügen kann, die problemlos von XAML-Auflistungssteuerelementen wie ListView, GridView oder ListBox genutzt wird.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-103">An asynchronous data source that can wrap the results of a Mobile Services query in a way that's easily consumed by Xaml collection controls like ListView, GridView or ListBox.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="4dd3b-104">Derzeit verarbeitet asynchron Laden der Daten, benachrichtigen der Steuerelemente und paging.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-104">Currently handles asynchronously loading the data, notifying the controls and paging.</span></span> <span data-ttu-id="4dd3b-105">Verwenden der <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`1" /> Klasse, wenn die Tabelle und die Auflistung Elemente desselben Typs sind.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-105">Use the <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`1" /> class if the table and collection items are of the same type.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceCollection (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.#ctor(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IMobileServiceTableQuery(Of TTable), Optional pageSize As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; (query, pageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="4dd3b-106">Die Datenquelle Abfrage, die die Daten bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-106">The data source's query which provides the data.</span></span>
            </param>
        <param name="pageSize">
            <span data-ttu-id="4dd3b-107">Die Anzahl der Elemente, die pro Anforderung angefordert.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-107">The number of items requested per request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dd3b-108">Initialisiert eine neue Instanz der <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-108">Initializes a new instance of the <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> class.</span></span> <span data-ttu-id="4dd3b-109">Dieser Konstruktor sollte in Fällen verwendet werden, wenn TTable und TCollection desselben Typs sind.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-109">This constructior should be used in cases where TTable and TCollection are the same type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceCollection (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query, Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt; selector, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query, class System.Func`2&lt;class System.Collections.Generic.IEnumerable`1&lt;!TTable&gt;, class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt;&gt; selector, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.#ctor(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0},System.Func{System.Collections.Generic.IEnumerable{`0},System.Collections.Generic.IEnumerable{`1}},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IMobileServiceTableQuery(Of TTable), selector As Func(Of IEnumerable(Of TTable), IEnumerable(Of TCollection)), Optional pageSize As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; * Func&lt;seq&lt;'able&gt;, seq&lt;'Collection&gt;&gt; * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; (query, selector, pageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
        <Parameter Name="selector" Type="System.Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt;" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="4dd3b-110">Die Datenquelle Abfrage, die die Daten bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-110">The data source's query which provides the data.</span></span>
            </param>
        <param name="selector">
            <span data-ttu-id="4dd3b-111">Eine Auswahlfunktion, um clientseitige Projektionen bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-111">A selector function to provide client side projections.</span></span>
            </param>
        <param name="pageSize">
            <span data-ttu-id="4dd3b-112">Die Anzahl der Elemente, die pro Anforderung angefordert.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-112">The number of items requested per request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dd3b-113">Initialisiert eine neue Instanz der <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-113">Initializes a new instance of the <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceCollection (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query, Func&lt;TTable,TCollection&gt; selector, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query, class System.Func`2&lt;!TTable, !TCollection&gt; selector, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.#ctor(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0},System.Func{`0,`1},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IMobileServiceTableQuery(Of TTable), selector As Func(Of TTable, TCollection), Optional pageSize As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; * Func&lt;'able, 'Collection&gt; * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; (query, selector, pageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
        <Parameter Name="selector" Type="System.Func&lt;TTable,TCollection&gt;" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="4dd3b-114">Die Datenquelle Abfrage, die die Daten bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-114">The data source's query which provides the data.</span></span>
            </param>
        <param name="selector">
            <span data-ttu-id="4dd3b-115">Eine Auswahlfunktion, um clientseitige Projektionen bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-115">A selector function to provide client side projections.</span></span>
            </param>
        <param name="pageSize">
            <span data-ttu-id="4dd3b-116">Die Anzahl der Elemente, die pro Anforderung angefordert.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-116">The number of items requested per request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dd3b-117">Initialisiert eine neue Instanz der <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-117">Initializes a new instance of the <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasMoreItems">
      <MemberSignature Language="C#" Value="public bool HasMoreItems { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.HasMoreItems" />
      <MemberSignature Language="VB.NET" Value="Public Property HasMoreItems As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreItems : bool with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.HasMoreItems" />
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
            <span data-ttu-id="4dd3b-118">Ruft einen Wert, der angibt, ob es sind weitere Elemente, die inkrementell geladen werden können.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-118">Gets a value indicating whether there are more items that can be loaded incrementally.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadingComplete">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; LoadingComplete;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; LoadingComplete" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadingComplete" />
      <MemberSignature Language="VB.NET" Value="Public Event LoadingComplete As EventHandler(Of LoadingCompleteEventArgs) " />
      <MemberSignature Language="F#" Value="member this.LoadingComplete : EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; " Usage="member this.LoadingComplete : System.EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dd3b-119">Tritt auf, wenn Sie fertig sind, Laden von Elementen.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-119">Occurs when finished loading items.</span></span> <span data-ttu-id="4dd3b-120">Bietet <see cref="T:Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs" /> mit, wie viele Elemente geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-120">Provides <see cref="T:Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs" /> with how many items were loaded.</span></span>  
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadingItems">
      <MemberSignature Language="C#" Value="public event EventHandler LoadingItems;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler LoadingItems" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadingItems" />
      <MemberSignature Language="VB.NET" Value="Public Event LoadingItems As EventHandler " />
      <MemberSignature Language="F#" Value="member this.LoadingItems : EventHandler " Usage="member this.LoadingItems : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dd3b-121">Tritt auf, wenn <see cref="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Int32)" /> beim Laden von Elementen ab.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-121">Occurs when <see cref="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Int32)" /> starting to load items.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMoreItemsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; LoadMoreItemsAsync (int count = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; LoadMoreItemsAsync(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadMoreItemsAsync (Optional count As Integer = 0) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LoadMoreItemsAsync : int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mobileServiceCollection.LoadMoreItemsAsync count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            <span data-ttu-id="4dd3b-122">Die Anzahl der Elemente, die geladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-122">The number of items to load.</span></span>
            <span data-ttu-id="4dd3b-123">Dieser Parameter überschreibt, die im Konstruktor angegebene Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-123">This parameter overrides the pageSize specified in the constructor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dd3b-124">Geladen Sie weitere Elemente asynchron werden.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-124">Load more items asynchronously.</span></span>
            <span data-ttu-id="4dd3b-125">Steuert, die welche das inkrementelle Laden für GridView unter Windows 8 unterstützt rufen diese Methode automatisch auf.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-125">Controls which support incremental loading on such as GridView on Windows 8 call this method automatically.</span></span>
            <span data-ttu-id="4dd3b-126">In anderen Fällen sollten Sie diese Methode selbst aufrufen.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-126">In other cases you should call this method yourself.</span></span>
            </summary>
        <returns><span data-ttu-id="4dd3b-127">Das Ergebnis des Laden der Elemente.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-127">The result of loading the items.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMoreItemsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; LoadMoreItemsAsync (System.Threading.CancellationToken token, int count = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; LoadMoreItemsAsync(valuetype System.Threading.CancellationToken token, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Threading.CancellationToken,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadMoreItemsAsync (token As CancellationToken, Optional count As Integer = 0) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LoadMoreItemsAsync : System.Threading.CancellationToken * int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mobileServiceCollection.LoadMoreItemsAsync (token, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2/&lt;LoadMoreItemsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="token">
            <span data-ttu-id="4dd3b-128">Das Abbruchtoken zum Abbrechen der Aufgabe verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-128">The cancellation token to be used to cancel the task.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="4dd3b-129">Die Anzahl der Elemente, die geladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-129">The number of items to load.</span></span>
            <span data-ttu-id="4dd3b-130">Dieser Parameter überschreibt, die im Konstruktor angegebene Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-130">This parameter overrides the pageSize specified in the constructor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dd3b-131">Geladen Sie weitere Elemente asynchron werden.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-131">Load more items asynchronously.</span></span>
            <span data-ttu-id="4dd3b-132">Steuert, die welche das inkrementelle Laden für GridView unter Windows 8 unterstützt rufen diese Methode automatisch auf.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-132">Controls which support incremental loading on such as GridView on Windows 8 call this method automatically.</span></span>
            <span data-ttu-id="4dd3b-133">In anderen Fällen sollten Sie diese Methode selbst aufrufen.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-133">In other cases you should call this method yourself.</span></span>
            </summary>
        <returns><span data-ttu-id="4dd3b-134">Das Ergebnis des Laden der Elemente.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-134">The result of loading the items.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dd3b-135">Ruft den Link zur nächsten Seite des Ergebnisses, das im Antwortheader zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-135">Gets the link to next page of result that is returned in response headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPropertyChanged">
      <MemberSignature Language="C#" Value="protected virtual void OnPropertyChanged (string propertyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnPropertyChanged(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.OnPropertyChanged(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnPropertyChanged (Optional propertyName As String = null)" />
      <MemberSignature Language="F#" Value="override this.OnPropertyChanged : string -&gt; unit" Usage="mobileServiceCollection.OnPropertyChanged propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="propertyName">
            <span data-ttu-id="4dd3b-136">Der Name der geänderten Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-136">The name of the property that has changed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dd3b-137">Ruft das PropertyChanged-Ereignis für die <paramref name="propertyName" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-137">Invokes the PropertyChanged event for the <paramref name="propertyName" /> property.</span></span>
            <span data-ttu-id="4dd3b-138">Bietet eine Möglichkeit zu überschreiben, das ereignisaufrufverhalten durch Unterklassen.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-138">Provides a way for subclasses to override the event invocation behavior.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="4dd3b-139">Das CallerMemberName-Attribut wird der Wert angeben, wenn kein expliziter Wert bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-139">The CallerMemberName attribute will supply the value if no explicit value is provided.</span></span>
            <span data-ttu-id="4dd3b-140">Weitere Informationen finden Sie unter http://msdn.microsoft.com/en-us/library/hh534540.aspx brauchen wir noch die null-Prüfung, da immer noch als expliziten Parameter null übergeben werden können.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-140">For more info see http://msdn.microsoft.com/en-us/library/hh534540.aspx We still need the null check, because you can still pass null as an explicit parameter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PageSize">
      <MemberSignature Language="C#" Value="public int PageSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.PageSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PageSize As Integer" />
      <MemberSignature Language="F#" Value="member this.PageSize : int" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.PageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dd3b-141">Im Konstruktor angegebene Seitengröße.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-141">The page size specified in the constructor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareDataForCollection">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TCollection&gt; PrepareDataForCollection (System.Collections.Generic.IEnumerable&lt;TTable&gt; items);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt; PrepareDataForCollection(class System.Collections.Generic.IEnumerable`1&lt;!TTable&gt; items) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.PrepareDataForCollection(System.Collections.Generic.IEnumerable{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PrepareDataForCollection (items As IEnumerable(Of TTable)) As IEnumerable(Of TCollection)" />
      <MemberSignature Language="F#" Value="abstract member PrepareDataForCollection : seq&lt;'able&gt; -&gt; seq&lt;'Collection&gt;&#xA;override this.PrepareDataForCollection : seq&lt;'able&gt; -&gt; seq&lt;'Collection&gt;" Usage="mobileServiceCollection.PrepareDataForCollection items" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.IEnumerable&lt;TTable&gt;" />
      </Parameters>
      <Docs>
        <param name="items"><span data-ttu-id="4dd3b-142">Die Elemente.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-142">The items.</span></span></param>
        <summary>
            <span data-ttu-id="4dd3b-143">Transformiert die Daten aus der Abfrage in der Auflistung unter Verwendung der bereitgestellten Auswahlfunktion-Daten.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-143">Transforms the data from the query into data for the collection using the provided selector function.</span></span>
            </summary>
        <returns><span data-ttu-id="4dd3b-144">Die transformierten Daten.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-144">The transformed data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareDataForCollection">
      <MemberSignature Language="C#" Value="public TCollection PrepareDataForCollection (TTable item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !TCollection PrepareDataForCollection(!TTable item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.PrepareDataForCollection(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function PrepareDataForCollection (item As TTable) As TCollection" />
      <MemberSignature Language="F#" Value="member this.PrepareDataForCollection : 'able -&gt; 'Collection" Usage="mobileServiceCollection.PrepareDataForCollection item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TCollection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="TTable" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="4dd3b-145">Das Element.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-145">The item.</span></span></param>
        <summary>
            <span data-ttu-id="4dd3b-146">Transformiert ein Element in ein Element für die Auflistung, die mit der bereitgestellten Auswahlfunktion.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-146">Transforms one item into an item for the collection using the provided selector function.</span></span>
            </summary>
        <returns><span data-ttu-id="4dd3b-147">Das transformierte Element.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-147">The transformed item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessQueryAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;int&gt; ProcessQueryAsync (System.Threading.CancellationToken token, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ProcessQueryAsync(valuetype System.Threading.CancellationToken token, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.ProcessQueryAsync(System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function ProcessQueryAsync (token As CancellationToken, query As IMobileServiceTableQuery(Of TTable)) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="abstract member ProcessQueryAsync : System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.ProcessQueryAsync : System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mobileServiceCollection.ProcessQueryAsync (token, query)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2/&lt;ProcessQueryAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="4dd3b-148">Ein Token, um den Vorgang abzubrechen.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-148">A token to cancel the operation.</span></span></param>
        <param name="query"><span data-ttu-id="4dd3b-149">Die auszuwertende Abfrage.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-149">The query to evaluate.</span></span></param>
        <summary>
            <span data-ttu-id="4dd3b-150">Wertet die Abfrage, und fügt das Ergebnis der Auflistung hinzu.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-150">Evaluates the query and adds the result to the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="4dd3b-151">Eine Aufgabe, die den laufenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-151">A task representing the ongoing operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="selectorFunction">
      <MemberSignature Language="C#" Value="protected Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt; selectorFunction;" />
      <MemberSignature Language="ILAsm" Value=".field family class System.Func`2&lt;class System.Collections.Generic.IEnumerable`1&lt;!TTable&gt;, class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt;&gt; selectorFunction" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.selectorFunction" />
      <MemberSignature Language="VB.NET" Value="Protected selectorFunction As Func(Of IEnumerable(Of TTable), IEnumerable(Of TCollection)) " />
      <MemberSignature Language="F#" Value="val mutable selectorFunction : Func&lt;seq&lt;'able&gt;, seq&lt;'Collection&gt;&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.selectorFunction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dd3b-152">Eine Auswahlfunktion Appied auf die Daten sein, wenn es vom Server wieder verfügbar wird.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-152">A selector function which will be appied to the data when it comes back from the server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dd3b-153">Ruft die Gesamtanzahl für alle Datensätze, die zurückgegeben worden wären wird vom Client oder Server angegebenen Take Paging/Limit-Klausel ignoriert.</span><span class="sxs-lookup"><span data-stu-id="4dd3b-153">Gets the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>