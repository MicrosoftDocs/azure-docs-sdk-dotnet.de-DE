<Type Name="ServiceHealthStateList" FullName="System.Fabric.Health.ServiceHealthStateList">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateList : System.Collections.Generic.ICollection&lt;System.Fabric.Health.ServiceHealthState&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ServiceHealthState&gt;, System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Health.ServiceHealthState&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Health.ServiceHealthState&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthState&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateList&#xA;Implements ICollection(Of ServiceHealthState), IEnumerable(Of ServiceHealthState), IList(Of ServiceHealthState)" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateList = class&#xA;    interface IList&lt;ServiceHealthState&gt;&#xA;    interface ICollection&lt;ServiceHealthState&gt;&#xA;    interface seq&lt;ServiceHealthState&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Health.ServiceHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ServiceHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="45194-101">Stellt eine Auflistung von <see cref="T:System.Fabric.Health.ServiceHealthState" /> einzeln nach Index zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="45194-101">Represents a collection of <see cref="T:System.Fabric.Health.ServiceHealthState" /> that can be individually accessed by index.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Add(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Health.ServiceHealthState -&gt; unit&#xA;override this.Add : System.Fabric.Health.ServiceHealthState -&gt; unit" Usage="serviceHealthStateList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="45194-102">Das Element, das hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="45194-102">The item to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-103">Fügt der Auflistung ein Element hinzu.</span><span class="sxs-lookup"><span data-stu-id="45194-103">Adds an item to the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceHealthStateList.Clear " />
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
          <para><span data-ttu-id="45194-104">Entfernt alle Elemente aus der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="45194-104">Removes all items from the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Contains(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Health.ServiceHealthState -&gt; bool&#xA;override this.Contains : System.Fabric.Health.ServiceHealthState -&gt; bool" Usage="serviceHealthStateList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="45194-105">Das Element in der Auflistung gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="45194-105">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-106">Ermittelt, ob die Auflistung einen bestimmten Wert enthält.</span><span class="sxs-lookup"><span data-stu-id="45194-106">Determines whether the collection contains a specific value.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="45194-107">Gibt <languageKeyword>"true"</languageKeyword> Wenn das Element gefunden wurde. <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="45194-107">Returns <languageKeyword>true</languageKeyword> if the item is found; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Health.ServiceHealthState[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Health.ServiceHealthState[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.CopyTo(System.Fabric.Health.ServiceHealthState[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceHealthState(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Health.ServiceHealthState[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Health.ServiceHealthState[] * int -&gt; unit" Usage="serviceHealthStateList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Health.ServiceHealthState[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="45194-108">Das eindimensionale Array, das das Ziel der aus ICollection kopierten Elemente ist.</span><span class="sxs-lookup"><span data-stu-id="45194-108">The one-dimensional Array that is the destination of the elements copied from ICollection.</span></span> <span data-ttu-id="45194-109">Für das Array muss eine nullbasierte Indizierung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="45194-109">The Array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="45194-110">Der nullbasierte Index im Array, ab dem kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="45194-110">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-111">Kopiert die Elemente der ICollection in ein Array, beginnend an einem bestimmten Arrayindex begonnen.</span><span class="sxs-lookup"><span data-stu-id="45194-111">Copies the elements of the ICollection to an Array, starting at a particular Array index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Health.ServiceHealthStateList.Count" />
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
          <para><span data-ttu-id="45194-112">Ruft die Anzahl der Elemente ab.</span><span class="sxs-lookup"><span data-stu-id="45194-112">Gets the number of elements.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="45194-113">Die Anzahl der Elemente.</span><span class="sxs-lookup"><span data-stu-id="45194-113">The number of elements.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Health.ServiceHealthState&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceHealthState)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt;" Usage="serviceHealthStateList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="45194-114">Gibt einen Enumerator zurück, der eine Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="45194-114">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="45194-115">Gibt <see cref="T:System.Collections.Generic.IEnumerator`1" /> -Objekt, das zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="45194-115">Returns <see cref="T:System.Collections.Generic.IEnumerator`1" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.IndexOf(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceHealthState) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Health.ServiceHealthState -&gt; int&#xA;override this.IndexOf : System.Fabric.Health.ServiceHealthState -&gt; int" Usage="serviceHealthStateList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="45194-116">Das Element in der Auflistung gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="45194-116">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-117">Bestimmt den Index eines bestimmten Elements in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="45194-117">Determines the index of a specific item in the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="45194-118">Der Index des Elements Wenn gefunden, die in der Auflistung. andernfalls -1.</span><span class="sxs-lookup"><span data-stu-id="45194-118">The index of the item if found in the collection; -1 otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Insert(System.Int32,System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Health.ServiceHealthState -&gt; unit&#xA;override this.Insert : int * System.Fabric.Health.ServiceHealthState -&gt; unit" Usage="serviceHealthStateList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="45194-119">Der nullbasierte Index, an dem der Wert eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="45194-119">The zero-based index at which value should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="45194-120">Das Element eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="45194-120">The item to be inserted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-121">Fügt ein Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="45194-121">Inserts an item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Health.ServiceHealthStateList.IsReadOnly" />
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
          <para><span data-ttu-id="45194-122">Ruft einen Wert ab, der angibt, ob die Liste schreibgeschützt ist.</span><span class="sxs-lookup"><span data-stu-id="45194-122">Gets a value indicating whether the list is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="45194-123"><languageKeyword>"true"</languageKeyword> ist die Liste schreibgeschützt ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="45194-123"><languageKeyword>true</languageKeyword> if the list is read-only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthState this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthState Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceHealthState" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Health.ServiceHealthState with get, set" Usage="System.Fabric.Health.ServiceHealthStateList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="45194-124">Der nullbasierte Index des Elements, das abgerufen oder festgelegt werden soll.</span><span class="sxs-lookup"><span data-stu-id="45194-124">The zero-based index of the element to get or set.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-125">Ruft das Element am angegebenen Index ab oder legt dieses fest.</span><span class="sxs-lookup"><span data-stu-id="45194-125">Gets or sets the element at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="45194-126">Gibt <see cref="T:System.Fabric.Health.ServiceHealthState" /> am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="45194-126">Returns <see cref="T:System.Fabric.Health.ServiceHealthState" /> at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Remove(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Health.ServiceHealthState -&gt; bool&#xA;override this.Remove : System.Fabric.Health.ServiceHealthState -&gt; bool" Usage="serviceHealthStateList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="45194-127">Das zu entfernende Element.</span><span class="sxs-lookup"><span data-stu-id="45194-127">The item to be removed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-128">Entfernt das erste Vorkommen eines bestimmten Elements aus der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="45194-128">Removes the first occurrence of a specific item from the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="45194-129">Gibt <languageKeyword>"true"</languageKeyword> , wenn das Element entfernt wurde; <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="45194-129">Returns <languageKeyword>true</languageKeyword> if the item was removed; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceHealthStateList.RemoveAt index" />
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
        <param name="index">
          <para><span data-ttu-id="45194-130">Der nullbasierte Index des zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="45194-130">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="45194-131">Entfernt das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="45194-131">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="45194-132">Gibt einen Enumerator zurück, der eine Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="45194-132">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="45194-133">Gibt <see cref="T:System.Collections.IEnumerator" /> -Objekt, das zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="45194-133">Returns <see cref="T:System.Collections.IEnumerator" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>