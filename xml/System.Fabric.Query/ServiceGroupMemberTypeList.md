<Type Name="ServiceGroupMemberTypeList" FullName="System.Fabric.Query.ServiceGroupMemberTypeList">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupMemberTypeList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMemberType&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMemberType&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMemberType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupMemberTypeList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceGroupMemberTypeList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupMemberTypeList&#xA;Implements ICollection(Of ServiceGroupMemberType), IEnumerable(Of ServiceGroupMemberType), IList(Of ServiceGroupMemberType)" />
  <TypeSignature Language="F#" Value="type ServiceGroupMemberTypeList = class&#xA;    interface IList&lt;ServiceGroupMemberType&gt;&#xA;    interface ICollection&lt;ServiceGroupMemberType&gt;&#xA;    interface seq&lt;ServiceGroupMemberType&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b25a1-101">Der Dienst Typliste der Gruppenmitglieder, die die Gruppe Member enthält.</span><span class="sxs-lookup"><span data-stu-id="b25a1-101">The service group member type list that contains the service group member types.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Add(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceGroupMemberType)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ServiceGroupMemberType -&gt; unit&#xA;override this.Add : System.Fabric.Query.ServiceGroupMemberType -&gt; unit" Usage="serviceGroupMemberTypeList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="b25a1-102">Der Dienst Gruppe-Elementtyp hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="b25a1-102">The service group member type to be added.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-103">Fügen Sie den Elementtyp des Dienst-Gruppe hinzu.</span><span class="sxs-lookup"><span data-stu-id="b25a1-103">Add the service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceGroupMemberTypeList.Clear " />
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
            <span data-ttu-id="b25a1-104">Deaktivieren Sie den Dienst Gruppe Elementtypen.</span><span class="sxs-lookup"><span data-stu-id="b25a1-104">Clear the service group member types.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Contains(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceGroupMemberType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ServiceGroupMemberType -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ServiceGroupMemberType -&gt; bool" Usage="serviceGroupMemberTypeList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="b25a1-105">Der Dienst Gruppe-Elementtyp, gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="b25a1-105">The service group member type to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-106">Durchsuchen, wenn den Elementtyp des Dienst-Gruppe enthält.</span><span class="sxs-lookup"><span data-stu-id="b25a1-106">Search if contains the service group member type.</span></span>
            </summary>
        <returns><span data-ttu-id="b25a1-107">Das Ergebnis der Suche.</span><span class="sxs-lookup"><span data-stu-id="b25a1-107">The result of the search.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ServiceGroupMemberType[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ServiceGroupMemberType[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.CopyTo(System.Fabric.Query.ServiceGroupMemberType[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceGroupMemberType(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ServiceGroupMemberType[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ServiceGroupMemberType[] * int -&gt; unit" Usage="serviceGroupMemberTypeList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ServiceGroupMemberType[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="b25a1-108">Der Dienst Gruppe-Elementtyp kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="b25a1-108">The service group member type to be copied.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="b25a1-109">Der Index, dem Kopieren begonnen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b25a1-109">The index to begin the copy.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-110">Kopieren Sie den Elementtyp des Dienst-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b25a1-110">Copy the service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberTypeList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ServiceGroupMemberTypeList.Count" />
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
            <span data-ttu-id="b25a1-111">Die Anzahl der Member der Diensttyp-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b25a1-111">The count of the service group member type.</span></span>
            </summary>
        <value><span data-ttu-id="b25a1-112">Die Anzahl der Member der Diensttyp-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b25a1-112">The count of the service group member type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceGroupMemberType)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt;" Usage="serviceGroupMemberTypeList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b25a1-113">Rufen Sie den Enumerator des Gruppenmitglieds Dienst Typen.</span><span class="sxs-lookup"><span data-stu-id="b25a1-113">Get the enumerator of the service group member types.</span></span>
            </summary>
        <returns><span data-ttu-id="b25a1-114">Der Enumerator der Diensttypen enthält Gruppe Mitglied ist.</span><span class="sxs-lookup"><span data-stu-id="b25a1-114">The enumerator of the service group member types.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.IndexOf(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceGroupMemberType) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ServiceGroupMemberType -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ServiceGroupMemberType -&gt; int" Usage="serviceGroupMemberTypeList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="b25a1-115">Der Dienst Gruppe-Elementtyp, gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="b25a1-115">The service group member type to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-116">Suchen Sie nach dem Index des Elements den Diensttyp-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b25a1-116">Search for the index of the service group member type.</span></span>
            </summary>
        <returns><span data-ttu-id="b25a1-117">Der Index des Elements den Diensttyp-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b25a1-117">The index of the service group member type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Insert(System.Int32,System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceGroupMemberType)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ServiceGroupMemberType -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ServiceGroupMemberType -&gt; unit" Usage="serviceGroupMemberTypeList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="b25a1-118">Der Index eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="b25a1-118">The index to be inserted.</span></span></param>
        <param name="item"><span data-ttu-id="b25a1-119">Der Dienst Gruppe-Elementtyp eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="b25a1-119">The service group member type to be inserted.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-120">Fügen Sie den Elementtyp des Dienst-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b25a1-120">Insert the service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberTypeList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ServiceGroupMemberTypeList.IsReadOnly" />
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
            <span data-ttu-id="b25a1-121">Das Flag nur lesen.</span><span class="sxs-lookup"><span data-stu-id="b25a1-121">The flag of read only.</span></span>
            </summary>
        <value><span data-ttu-id="b25a1-122">Das Flag nur lesen.</span><span class="sxs-lookup"><span data-stu-id="b25a1-122">The flag of read only.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceGroupMemberType this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ServiceGroupMemberType Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberTypeList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceGroupMemberType" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ServiceGroupMemberType with get, set" Usage="System.Fabric.Query.ServiceGroupMemberTypeList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceGroupMemberType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="b25a1-123">Der Index des Diensttyps Gruppe Member zugegriffen werden.</span><span class="sxs-lookup"><span data-stu-id="b25a1-123">The index of service group member type to be accessed.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-124">Zugriff auf den Dienst Gruppe Elementtyp.</span><span class="sxs-lookup"><span data-stu-id="b25a1-124">Access the service group member type.</span></span>
            </summary>
        <value><span data-ttu-id="b25a1-125">Der Index des Diensttyps Gruppe Mitglied.</span><span class="sxs-lookup"><span data-stu-id="b25a1-125">Index of the service group member type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Remove(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceGroupMemberType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ServiceGroupMemberType -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ServiceGroupMemberType -&gt; bool" Usage="serviceGroupMemberTypeList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="b25a1-126">Der Dienst Gruppe-Elementtyp entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="b25a1-126">The service group member type to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-127">Entfernen Sie den Elementtyp des Dienst-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b25a1-127">Remove the service group member type.</span></span>
            </summary>
        <returns><span data-ttu-id="b25a1-128">Das Ergebnis des entfernen.</span><span class="sxs-lookup"><span data-stu-id="b25a1-128">The result of the remove.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceGroupMemberTypeList.RemoveAt index" />
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
        <param name="index"><span data-ttu-id="b25a1-129">Der Index des Diensttyps Gruppe Mitglied entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="b25a1-129">The index of service group member type to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="b25a1-130">Elementtyp für Service-Gruppe zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="b25a1-130">Remove service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.System#Collections#IEnumerable#GetEnumerator" />
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
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>