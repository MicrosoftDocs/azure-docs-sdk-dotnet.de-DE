<Type Name="ServiceTypeList" FullName="System.Fabric.Query.ServiceTypeList">
  <TypeSignature Language="C#" Value="public sealed class ServiceTypeList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceType&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceType&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceTypeList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ServiceType&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ServiceType&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ServiceType&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceTypeList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceTypeList&#xA;Implements ICollection(Of ServiceType), IEnumerable(Of ServiceType), IList(Of ServiceType)" />
  <TypeSignature Language="F#" Value="type ServiceTypeList = class&#xA;    interface IList&lt;ServiceType&gt;&#xA;    interface ICollection&lt;ServiceType&gt;&#xA;    interface seq&lt;ServiceType&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceType&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="3ca8b-101">Stellt eine Liste der Diensttyp.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-101">Represents a list of service type.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Add(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceType)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ServiceType -&gt; unit&#xA;override this.Add : System.Fabric.Query.ServiceType -&gt; unit" Usage="serviceTypeList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3ca8b-102">Das Element, das hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-102">The item to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-103">Fügt am Ende der <see cref="T:System.Fabric.Query.ServiceTypeList" /> ein Objekt hinzu.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-103">Adds an object to the end of the <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceTypeList.Clear " />
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
          <para><span data-ttu-id="3ca8b-104">Entfernt alle Elemente aus der <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-104">Removes all elements from the <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Contains(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ServiceType -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ServiceType -&gt; bool" Usage="serviceTypeList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3ca8b-105">Das Element zu suchen.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-105">The item to search.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-106">Bestimmt, ob ein Element in der <see cref="T:System.Fabric.Query.ServiceTypeList" />...</span><span class="sxs-lookup"><span data-stu-id="3ca8b-106">Determines whether an element is in the <see cref="T:System.Fabric.Query.ServiceTypeList" />..</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="3ca8b-107"><languageKeyword>"true"</languageKeyword> Wenn das Element in der <see cref="T:System.Fabric.Query.ServiceTypeList" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-107"><languageKeyword>true</languageKeyword> if the item is in the <see cref="T:System.Fabric.Query.ServiceTypeList" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ServiceType[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ServiceType[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.CopyTo(System.Fabric.Query.ServiceType[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceType(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ServiceType[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ServiceType[] * int -&gt; unit" Usage="serviceTypeList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ServiceType[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="3ca8b-108">Ein Array von Diensttyp.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-108">An array of service type.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="3ca8b-109">Der Index des Arrays.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-109">The array index.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-110">Kopiert die gesamte <see cref="T:System.Fabric.Query.ServiceTypeList" />-Instanz in ein kompatibles eindimensionales <see cref="T:System.Fabric.Query.ServiceTypeList" />, beginnend am angegebenen Index des Zielarrays.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-110">Copies the entire <see cref="T:System.Fabric.Query.ServiceTypeList" /> to a compatible one-dimensional <see cref="T:System.Fabric.Query.ServiceTypeList" />, starting at the specified index of the target array.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceTypeList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ServiceTypeList.Count" />
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
          <para><span data-ttu-id="3ca8b-111">Ruft ab oder legt die Anzahl der Elemente in der <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-111">Gets or sets the number of elements in the <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3ca8b-112">Die Anzahl der Elemente im <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-112">The number of elements in the <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ServiceType&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceType)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt;" Usage="serviceTypeList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="3ca8b-113">Gibt einen Enumerator für die gesamte <see cref="T:System.Fabric.Query.ServiceTypeList" />...</span><span class="sxs-lookup"><span data-stu-id="3ca8b-113">Returns an enumerator for the entire <see cref="T:System.Fabric.Query.ServiceTypeList" />..</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="3ca8b-114">Ein Enumerator für die gesamte <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-114">An enumerator for the entire <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.IndexOf(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceType) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ServiceType -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ServiceType -&gt; int" Usage="serviceTypeList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3ca8b-115">Das Element zu suchen.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-115">The item to search.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-116">Sucht nach dem angegebenen <see cref="T:System.Fabric.Query.ServiceType" /> und gibt den nullbasierten Index des ersten Vorkommens innerhalb der gesamten <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-116">Searches for the specified <see cref="T:System.Fabric.Query.ServiceType" />  and returns the zero-based index of the first occurrence within the entire <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="3ca8b-117">Der nullbasierte Index des ersten Vorkommens innerhalb der gesamten <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-117">The zero-based index of the first occurrence within the entire <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Insert(System.Int32,System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceType)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ServiceType -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ServiceType -&gt; unit" Usage="serviceTypeList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="3ca8b-118">Der Index.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-118">The index.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="3ca8b-119">Das einzufügende Element.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-119">The item to insert.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-120">Fügt ein Element in der <see cref="T:System.Fabric.Query.ServiceTypeList" /> am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-120">Inserts an element into the <see cref="T:System.Fabric.Query.ServiceTypeList" />  at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceTypeList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ServiceTypeList.IsReadOnly" />
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
          <para><span data-ttu-id="3ca8b-121">Ruft ab oder legt sie fest, ob <see cref="T:System.Fabric.Query.ServiceTypeList" /> ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-121">Gets or sets whether <see cref="T:System.Fabric.Query.ServiceTypeList" /> is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="3ca8b-122"><languageKeyword>"true"</languageKeyword> Wenn die <see cref="T:System.Fabric.Query.ServiceTypeList" /> schreibgeschützt ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-122"><languageKeyword>true</languageKeyword> if the <see cref="T:System.Fabric.Query.ServiceTypeList" /> is read-only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceType this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ServiceType Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceTypeList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceType" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ServiceType with get, set" Usage="System.Fabric.Query.ServiceTypeList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="3ca8b-123">Der nullbasierte Index des Elements, das abgerufen oder festgelegt werden soll.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-123">The zero-based index of the element to get or set.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-124">Ruft das Element am angegebenen Index ab oder legt dieses fest.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-124">Gets or sets the element at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3ca8b-125">Das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-125">The element at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Remove(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ServiceType -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ServiceType -&gt; bool" Usage="serviceTypeList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3ca8b-126">Das zu entfernende Element.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-126">The item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-127">Entfernt das erste Vorkommen eines bestimmten Objekts aus der <see cref="T:System.Fabric.Query.ServiceTypeList" />...</span><span class="sxs-lookup"><span data-stu-id="3ca8b-127">Removes the first occurrence of a specific object from the <see cref="T:System.Fabric.Query.ServiceTypeList" />..</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="3ca8b-128"><languageKeyword>"true"</languageKeyword> , wenn das Element vorhanden ist; andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-128"><languageKeyword>true</languageKeyword> if the item exist; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceTypeList.RemoveAt index" />
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
          <para><span data-ttu-id="3ca8b-129">Der Index, wo Sie das Element zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-129">The index where to remove the item.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3ca8b-130">Entfernt das Element am angegebenen Index aus der <see cref="T:System.Fabric.Query.ServiceTypeList" />...</span><span class="sxs-lookup"><span data-stu-id="3ca8b-130">Removes the element at the specified index of the <see cref="T:System.Fabric.Query.ServiceTypeList" />..</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="3ca8b-131">Gibt den Enumerator für die <see cref="T:System.Fabric.Query.ServiceTypeList" />...</span><span class="sxs-lookup"><span data-stu-id="3ca8b-131">Returns the enumerator for the <see cref="T:System.Fabric.Query.ServiceTypeList" />..</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="3ca8b-132">Der Zähler für die <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="3ca8b-132">The numerator for the <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>