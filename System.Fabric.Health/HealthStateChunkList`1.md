<Type Name="HealthStateChunkList&lt;T&gt;" FullName="System.Fabric.Health.HealthStateChunkList&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class HealthStateChunkList&lt;T&gt; : System.Collections.Generic.ICollection&lt;T&gt;, System.Collections.Generic.IEnumerable&lt;T&gt;, System.Collections.Generic.IList&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit HealthStateChunkList`1&lt;T&gt; extends System.Object implements class System.Collections.Generic.ICollection`1&lt;!T&gt;, class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.Generic.IList`1&lt;!T&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthStateChunkList`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class HealthStateChunkList(Of T)&#xA;Implements ICollection(Of T), IEnumerable(Of T), IList(Of T)" />
  <TypeSignature Language="F#" Value="type HealthStateChunkList&lt;'T&gt; = class&#xA;    interface IList&lt;'T&gt;&#xA;    interface ICollection&lt;'T&gt;&#xA;    interface seq&lt;'T&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="42d00-101">Der Typ der Elemente in der Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-101">The type of the items in the list.</span></span></typeparam>
    <summary>
            <span data-ttu-id="42d00-102">Stellt eine Block-Liste, die eine Liste der Integrität Statuselemente-Segment enthält.</span><span class="sxs-lookup"><span data-stu-id="42d00-102">Represents a chunk list that contains a list of health state chunk items.</span></span>
            </summary>
    <remarks>
      <para><span data-ttu-id="42d00-103">Die Liste der Block wird aus Abfragen abgerufen, die potenziell Weitere Ergebnisse als eine Nachricht passt aufweisen können.</span><span class="sxs-lookup"><span data-stu-id="42d00-103">The chunk list is obtained from queries that can potentially have more results than can fit a message.</span></span> <span data-ttu-id="42d00-104">Nur die Einträge, die angepasst werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="42d00-104">Only the entries that fit are returned.</span></span> <span data-ttu-id="42d00-105">Die Liste enthalten die Gesamtanzahl der Elemente, die zurückgegeben wurde sollen, wenn genügend Speicherplatz vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="42d00-105">The list included the total number of items that should have been returned if there was enough space.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HealthStateChunkList ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42d00-106">Instanziiert eine leere <see cref="T:System.Fabric.Health.HealthStateChunkList`1" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="42d00-106">Instantiates an empty <see cref="T:System.Fabric.Health.HealthStateChunkList`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HealthStateChunkList (System.Collections.Generic.IList&lt;T&gt; list);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;!T&gt; list) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.#ctor(System.Collections.Generic.IList{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (list As IList(Of T))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthStateChunkList&lt;'T&gt; : System.Collections.Generic.IList&lt;'T&gt; -&gt; System.Fabric.Health.HealthStateChunkList&lt;'T&gt;" Usage="new System.Fabric.Health.HealthStateChunkList&lt;'T&gt; list" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="list" Type="System.Collections.Generic.IList&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="list"><span data-ttu-id="42d00-107">Die Liste mit Elementen, die zum Erstellen der ausgelagerten Liste verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="42d00-107">The list with items used to create the paged list.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-108">Instanziiert eine <see cref="T:System.Fabric.Health.HealthStateChunkList`1" /> Klasse mit den Elementen einer anderen Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-108">Instantiates a <see cref="T:System.Fabric.Health.HealthStateChunkList`1" /> class with the items of another list.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(!T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.Add(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As T)" />
      <MemberSignature Language="F#" Value="abstract member Add : 'T -&gt; unit&#xA;override this.Add : 'T -&gt; unit" Usage="healthStateChunkList.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="42d00-109">Das Element, das der Liste hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="42d00-109">The item to add to the list.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-110">Fügt ein Element zu dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-110">Adds an item to this list.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="healthStateChunkList.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42d00-111">Entfernt alle Elemente aus dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-111">Removes all items from this list.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(!T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.Contains(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As T) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : 'T -&gt; bool&#xA;override this.Contains : 'T -&gt; bool" Usage="healthStateChunkList.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="42d00-112">Das Element zu suchen.</span><span class="sxs-lookup"><span data-stu-id="42d00-112">The item to search.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-113">Gibt an, ob die Liste ein bestimmtes Element enthält.</span><span class="sxs-lookup"><span data-stu-id="42d00-113">Specifies whether the list contains a specific item.</span></span>
            </summary>
        <returns><span data-ttu-id="42d00-114">"true", wenn die Liste ein bestimmtes Element enthält; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="42d00-114">true if the list contains a specific item; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (T[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(!T[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.CopyTo(`0[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As T(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : 'T[] * int -&gt; unit&#xA;override this.CopyTo : 'T[] * int -&gt; unit" Usage="healthStateChunkList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.CopyTo(`0[],System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="T[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="42d00-115">Das Array.</span><span class="sxs-lookup"><span data-stu-id="42d00-115">The array.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="42d00-116">Der Index des Arrays.</span><span class="sxs-lookup"><span data-stu-id="42d00-116">The array index.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-117">Kopiert die Elemente aus dieser Liste in das angegebene Array, beginnend am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="42d00-117">Copies items from this list to the specified array starting at the specified index.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStateChunkList`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Health.HealthStateChunkList&lt;'T&gt;.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42d00-118">Ruft ab oder legt die Anzahl der Elemente in der Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-118">Gets or sets the number of items in the list.</span></span>
            </summary>
        <value><span data-ttu-id="42d00-119">Die Anzahl der Elemente in der Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-119">The number of items in the list.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;T&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!T&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;" Usage="healthStateChunkList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42d00-120">Ruft einen Enumerator für Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-120">Gets an enumerator to items in this list.</span></span> 
            </summary>
        <returns><span data-ttu-id="42d00-121">Der Enumerator Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-121">The enumerator to items in this list.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(!T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.IndexOf(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As T) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : 'T -&gt; int&#xA;override this.IndexOf : 'T -&gt; int" Usage="healthStateChunkList.IndexOf item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.IndexOf(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="42d00-122">Das Element.</span><span class="sxs-lookup"><span data-stu-id="42d00-122">The item.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-123">Ruft den Index in der Liste für das angegebene Element ab.</span><span class="sxs-lookup"><span data-stu-id="42d00-123">Gets the index in this list for the specified item.</span></span>
            </summary>
        <returns><span data-ttu-id="42d00-124">Der Index in der Liste für das angegebene Element.</span><span class="sxs-lookup"><span data-stu-id="42d00-124">The index in this list for the specified item.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, !T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.Insert(System.Int32,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As T)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * 'T -&gt; unit&#xA;override this.Insert : int * 'T -&gt; unit" Usage="healthStateChunkList.Insert (index, item)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.Insert(System.Int32,`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="42d00-125">Der Index, in dem das Element eingefügt wird.</span><span class="sxs-lookup"><span data-stu-id="42d00-125">The index where the item will be inserted.</span></span></param>
        <param name="item"><span data-ttu-id="42d00-126">Das einzufügende Element.</span><span class="sxs-lookup"><span data-stu-id="42d00-126">The item to insert.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-127">Fügt ein Element in dieser Liste am angegebenen Index ein.</span><span class="sxs-lookup"><span data-stu-id="42d00-127">Inserts an item into this list at the specified index.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStateChunkList`1.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Health.HealthStateChunkList&lt;'T&gt;.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42d00-128">Ruft ab oder legt ein Flag, das angibt, ob die Liste geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="42d00-128">Gets or sets a flag that indicated whether the list can be modified.</span></span>
            </summary>
        <value><span data-ttu-id="42d00-129">Ein Flag, der angibt, ob die Liste geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="42d00-129">Flag indicating whether the list can be modified.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public T this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStateChunkList`1.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As T" />
      <MemberSignature Language="F#" Value="member this.Item(int) : 'T with get, set" Usage="System.Fabric.Health.HealthStateChunkList&lt;'T&gt;.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="42d00-130">Der Index.</span><span class="sxs-lookup"><span data-stu-id="42d00-130">The index.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-131">Ruft das Element am angegebenen Index ab.</span><span class="sxs-lookup"><span data-stu-id="42d00-131">Gets the item at the specified index.</span></span>
            </summary>
        <value><span data-ttu-id="42d00-132">Das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="42d00-132">The item at the specified index.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(!T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.Remove(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As T) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : 'T -&gt; bool&#xA;override this.Remove : 'T -&gt; bool" Usage="healthStateChunkList.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="42d00-133">Das zu entfernende Element.</span><span class="sxs-lookup"><span data-stu-id="42d00-133">The item to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-134">Entfernt das angegebene Element aus dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-134">Removes the specified item from this list.</span></span> 
            </summary>
        <returns><span data-ttu-id="42d00-135">"true", wenn das Element entfernt wird; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="42d00-135">true if the item is removed; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="healthStateChunkList.RemoveAt index" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.RemoveAt(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="42d00-136">Der Index, in dem das Element entfernt wird.</span><span class="sxs-lookup"><span data-stu-id="42d00-136">The index where the item will be removed.</span></span></param>
        <summary>
            <span data-ttu-id="42d00-137">Entfernt das Element am angegebenen Index aus dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-137">Removes the item at the specified index from this list.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42d00-138">Ruft einen Enumerator für Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-138">Gets an enumerator to items in this list.</span></span> 
            </summary>
        <returns><span data-ttu-id="42d00-139">Der Enumerator Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-139">The enumerator to items in this list.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateChunkList`1.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthStateChunkList.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42d00-140">Gibt eine Zeichenfolgendarstellung der Segment-Liste zurück.</span><span class="sxs-lookup"><span data-stu-id="42d00-140">Returns a string representation of the chunk list.</span></span>
            </summary>
        <returns><span data-ttu-id="42d00-141">Eine Zeichenfolgendarstellung der Segment-Liste.</span><span class="sxs-lookup"><span data-stu-id="42d00-141">A string representation of the chunk list.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStateChunkList`1.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64 with get, set" Usage="System.Fabric.Health.HealthStateChunkList&lt;'T&gt;.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42d00-142">Ruft die Gesamtanzahl der Elemente, die in eine oder mehrere Nachrichten zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="42d00-142">Gets the total number of items to be returned in one or more messages.</span></span>
            </summary>
        <value><span data-ttu-id="42d00-143">Die Gesamtanzahl der Elemente im System, aus dem die aktuellen Elemente zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="42d00-143">The total number of items available in the system, out of which the current items were returned.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>