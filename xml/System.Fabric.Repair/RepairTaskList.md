<Type Name="RepairTaskList" FullName="System.Fabric.Repair.RepairTaskList">
  <TypeSignature Language="C#" Value="public sealed class RepairTaskList : System.Collections.Generic.ICollection&lt;System.Fabric.Repair.RepairTask&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Repair.RepairTask&gt;, System.Collections.Generic.IList&lt;System.Fabric.Repair.RepairTask&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RepairTaskList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Repair.RepairTask&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Repair.RepairTask&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Repair.RepairTask&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RepairTaskList&#xA;Implements ICollection(Of RepairTask), IEnumerable(Of RepairTask), IList(Of RepairTask)" />
  <TypeSignature Language="F#" Value="type RepairTaskList = class&#xA;    interface IList&lt;RepairTask&gt;&#xA;    interface ICollection&lt;RepairTask&gt;&#xA;    interface seq&lt;RepairTask&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Repair.RepairTask&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Repair.RepairTask&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Repair.RepairTask&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="8b0c7-101">Stellt eine Liste von <see cref="T:System.Fabric.Repair.RepairTask" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-101">Represents a list of <see cref="T:System.Fabric.Repair.RepairTask" /> objects.</span></span></para>
      <para><span data-ttu-id="8b0c7-102">Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Add(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As RepairTask)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Repair.RepairTask -&gt; unit&#xA;override this.Add : System.Fabric.Repair.RepairTask -&gt; unit" Usage="repairTaskList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="8b0c7-103">Das Objekt, das der Liste hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-103">The object to add to the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-104">Fügt der <see cref="T:System.Fabric.Repair.RepairTaskList" /> ein Element hinzu.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-104">Adds an item to the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="repairTaskList.Clear " />
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
          <para><span data-ttu-id="8b0c7-105">Entfernt alle Elemente aus <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-105">Removes all items from the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Contains(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As RepairTask) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Repair.RepairTask -&gt; bool&#xA;override this.Contains : System.Fabric.Repair.RepairTask -&gt; bool" Usage="repairTaskList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="8b0c7-106">Das Objekt, das in der Liste gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-106">The object to locate in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-107">Ermittelt, ob die <see cref="T:System.Fabric.Repair.RepairTaskList" /> einen bestimmten Wert enthält.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-107">Determines whether the <see cref="T:System.Fabric.Repair.RepairTaskList" /> contains a specific value.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="8b0c7-108"><languageKeyword>"true"</languageKeyword> Wenn die <see cref="T:System.Fabric.Repair.RepairTaskList" /> einen bestimmten Wert enthält, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-108"><languageKeyword>true</languageKeyword> if the <see cref="T:System.Fabric.Repair.RepairTaskList" /> contains a specific value; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Repair.RepairTask[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Repair.RepairTask[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.CopyTo(System.Fabric.Repair.RepairTask[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As RepairTask(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Repair.RepairTask[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Repair.RepairTask[] * int -&gt; unit" Usage="repairTaskList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Repair.RepairTask[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="8b0c7-109">Das eindimensionale Array, das das Ziel der aus kopierten Elemente ist <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-109">The one-dimensional Array that is the destination of elements copied from <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span> <span data-ttu-id="8b0c7-110">Für das Array muss eine nullbasierte Indizierung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-110">The Array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="8b0c7-111">Der nullbasierte Index im Array, ab dem kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-111">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-112">Kopiert die Elemente der <see cref="T:System.Fabric.Repair.RepairTaskList" /> beginnend an einem bestimmten Arrayindex in ein Array.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-112">Copies the elements of the <see cref="T:System.Fabric.Repair.RepairTaskList" /> to an Array, starting at a particular Array index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTaskList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Repair.RepairTaskList.Count" />
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
          <para><span data-ttu-id="8b0c7-113">Ruft die Anzahl der Elemente ab, die in <see cref="T:System.Fabric.Repair.RepairTaskList" /> enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-113">Gets the number of elements contained in the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8b0c7-114">Die Anzahl der Elemente, die in <see cref="T:System.Fabric.Repair.RepairTaskList" /> enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-114">The number of elements contained in the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Repair.RepairTask&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of RepairTask)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt;" Usage="repairTaskList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="8b0c7-115">Gibt einen Enumerator zurück, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-115">Returns an enumerator that iterates through the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="8b0c7-116">Ein Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-116">An enumerator that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.IndexOf(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As RepairTask) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Repair.RepairTask -&gt; int&#xA;override this.IndexOf : System.Fabric.Repair.RepairTask -&gt; int" Usage="repairTaskList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="8b0c7-117">Das Objekt, das in der Liste gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-117">The object to locate in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-118">Bestimmt den Index eines bestimmten Elements in der <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-118">Determines the index of a specific item in the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="8b0c7-119">Der Index des Elements Wenn in der Liste gefunden andernfalls -1.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-119">The index of item if found in the list; otherwise, -1.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Insert(System.Int32,System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As RepairTask)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Repair.RepairTask -&gt; unit&#xA;override this.Insert : int * System.Fabric.Repair.RepairTask -&gt; unit" Usage="repairTaskList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="8b0c7-120">Der nullbasierte Index, an dem das Element eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-120">The zero-based index at which item should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="8b0c7-121">Das Objekt, das in die Liste eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-121">The object to insert into the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-122">Fügt am angegebenen Index ein Element in die <see cref="T:System.Fabric.Repair.RepairTaskList" /> ein.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-122">Inserts an item to the <see cref="T:System.Fabric.Repair.RepairTaskList" /> at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTaskList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Repair.RepairTaskList.IsReadOnly" />
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
          <para><span data-ttu-id="8b0c7-123">Ruft einen Wert ab, der angibt, ob das <see cref="T:System.Fabric.Repair.RepairTaskList" /> schreibgeschützt ist.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-123">Gets a value indicating whether the <see cref="T:System.Fabric.Repair.RepairTaskList" /> is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="8b0c7-124"><languageKeyword>"true"</languageKeyword> Wenn die <see cref="T:System.Fabric.Repair.RepairTaskList" /> schreibgeschützt ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-124"><languageKeyword>true</languageKeyword> if the <see cref="T:System.Fabric.Repair.RepairTaskList" /> is read-only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTask this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairTask Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTaskList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As RepairTask" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Repair.RepairTask with get, set" Usage="System.Fabric.Repair.RepairTaskList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="8b0c7-125">Der nullbasierte Index des Elements, das abgerufen oder festgelegt werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-125">The zero-based index of the element to get or set.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-126">Ruft das Element am angegebenen Index ab oder legt dieses fest.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-126">Gets or sets the element at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8b0c7-127">Das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-127">The element at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Remove(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As RepairTask) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Repair.RepairTask -&gt; bool&#xA;override this.Remove : System.Fabric.Repair.RepairTask -&gt; bool" Usage="repairTaskList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="8b0c7-128">Das Objekt, das aus der Liste entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-128">The object to remove from the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-129">Entfernt das erste Vorkommen eines angegebenen Objekts aus der <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-129">Removes the first occurrence of a specific object from the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="8b0c7-130"><languageKeyword>"true"</languageKeyword> Wenn das Element erfolgreich aus der Liste entfernt wurde, andernfalls wurde <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-130"><languageKeyword>true</languageKeyword> if the item was successfully removed from the list; otherwise, <languageKeyword>false</languageKeyword>.</span></span> <span data-ttu-id="8b0c7-131">Diese Methode gibt auch "false", wenn das Element nicht in der ursprünglichen Liste gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-131">This method also returns false if item is not found in the original list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="repairTaskList.RemoveAt index" />
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
          <para><span data-ttu-id="8b0c7-132">Der nullbasierte Index des zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-132">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8b0c7-133">Entfernt das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-133">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="8b0c7-134">Gibt einen Enumerator zurück, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-134">Returns an enumerator that iterates through the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="8b0c7-135">Ein Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="8b0c7-135">An enumerator that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>