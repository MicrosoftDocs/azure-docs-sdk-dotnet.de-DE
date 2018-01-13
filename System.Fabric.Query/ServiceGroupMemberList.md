<Type Name="ServiceGroupMemberList" FullName="System.Fabric.Query.ServiceGroupMemberList">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupMemberList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMember&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMember&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMember&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupMemberList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ServiceGroupMember&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ServiceGroupMember&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ServiceGroupMember&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceGroupMemberList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupMemberList&#xA;Implements ICollection(Of ServiceGroupMember), IEnumerable(Of ServiceGroupMember), IList(Of ServiceGroupMember)" />
  <TypeSignature Language="F#" Value="type ServiceGroupMemberList = class&#xA;    interface IList&lt;ServiceGroupMember&gt;&#xA;    interface ICollection&lt;ServiceGroupMember&gt;&#xA;    interface seq&lt;ServiceGroupMember&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMember&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMember&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMember&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f3ac0-101">Der Dienstliste der Gruppenmitglieder, die Mitglieder der Dienst enthält.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-101">The service group member list that contains service group members.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Add(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceGroupMember)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ServiceGroupMember -&gt; unit&#xA;override this.Add : System.Fabric.Query.ServiceGroupMember -&gt; unit" Usage="serviceGroupMemberList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="f3ac0-102">Die Dienst-Mitglied der Gruppe hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-102">The service group member to be added.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-103">Fügen Sie Gruppenmitglied Dienst hinzu.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-103">Add service group member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceGroupMemberList.Clear " />
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
            <span data-ttu-id="f3ac0-104">Deaktivieren Sie die Gruppenmitglieder Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-104">Clear the service group members.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Contains(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceGroupMember) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ServiceGroupMember -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ServiceGroupMember -&gt; bool" Usage="serviceGroupMemberList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="f3ac0-105">Der Dienst Gruppenmitglied, gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-105">The service group member to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-106">Durchsuchen, wenn Gruppenmitglied Dienst enthält.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-106">Search if contains service group member.</span></span>
            </summary>
        <returns><span data-ttu-id="f3ac0-107">Das Ergebnis der Suche.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-107">The result of the search.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ServiceGroupMember[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ServiceGroupMember[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.CopyTo(System.Fabric.Query.ServiceGroupMember[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceGroupMember(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ServiceGroupMember[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ServiceGroupMember[] * int -&gt; unit" Usage="serviceGroupMemberList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ServiceGroupMember[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="f3ac0-108">Der Dienst Gruppenmitglieder kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-108">The service group members to be copied.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="f3ac0-109">Der Index des Arrays, das Kopieren begonnen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-109">The index of the array to begin copy.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-110">Kopieren Sie die Gruppenmitglieder Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-110">Copy the service group members.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ServiceGroupMemberList.Count" />
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
            <span data-ttu-id="f3ac0-111">Die Anzahl der Gruppenmitglieder Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-111">The count of the service group members.</span></span>
            </summary>
        <value><span data-ttu-id="f3ac0-112">Die Anzahl der Gruppenmitglieder Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-112">The count of the service group members.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ServiceGroupMember&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceGroupMember)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt;" Usage="serviceGroupMemberList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3ac0-113">Der Enumerator der Gruppenmitglieder Dienst abrufen.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-113">Get the enumerator of the service group members.</span></span>
            </summary>
        <returns><span data-ttu-id="f3ac0-114">Der Enumerator der Gruppenmitglieder Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-114">The enumerator of the service group members.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.IndexOf(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceGroupMember) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ServiceGroupMember -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ServiceGroupMember -&gt; int" Usage="serviceGroupMemberList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="f3ac0-115">Der Dienst Gruppenmitglied, gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-115">The service group member to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-116">Suchen Sie den Index des Gruppenmitglieds Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-116">Find the index of the service group member.</span></span>
            </summary>
        <returns><span data-ttu-id="f3ac0-117">Der Index des Gruppenmitglieds Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-117">The index of the service group member.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Insert(System.Int32,System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceGroupMember)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ServiceGroupMember -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ServiceGroupMember -&gt; unit" Usage="serviceGroupMemberList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="f3ac0-118">Der Index eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-118">The index to be inserted.</span></span></param>
        <param name="item"><span data-ttu-id="f3ac0-119">Der Dienst Gruppenmitglied eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-119">The service group member to be inserted.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-120">Fügen Sie das Gruppenelement Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-120">Insert the service group member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ServiceGroupMemberList.IsReadOnly" />
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
            <span data-ttu-id="f3ac0-121">Das Flag nur lesen.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-121">The flag of read only.</span></span>
            </summary>
        <value><span data-ttu-id="f3ac0-122">Das Flag nur lesen.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-122">The flag of read only.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceGroupMember this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ServiceGroupMember Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceGroupMember" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ServiceGroupMember with get, set" Usage="System.Fabric.Query.ServiceGroupMemberList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceGroupMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="f3ac0-123">Der Index des Gruppenmitglieds Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-123">The index of the service group member.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-124">Zugriff auf das Gruppenelement Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-124">Access the service group member.</span></span>
            </summary>
        <value><span data-ttu-id="f3ac0-125">Der Index des Gruppenmitglieds Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-125">Index of the service group member.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Remove(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceGroupMember) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ServiceGroupMember -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ServiceGroupMember -&gt; bool" Usage="serviceGroupMemberList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="f3ac0-126">Der Dienst Gruppenmitglied entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-126">The service group member to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-127">Entfernen Sie das Gruppenelement Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-127">Remove the service group member.</span></span>
            </summary>
        <returns><span data-ttu-id="f3ac0-128">Das Ergebnis des entfernen.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-128">The result of the remove.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceGroupMemberList.RemoveAt index" />
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
        <param name="index"><span data-ttu-id="f3ac0-129">Der Index des Dienst-Gruppenmitglied entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-129">The index of service group member to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="f3ac0-130">Entfernen Sie das Gruppenelement Dienst.</span><span class="sxs-lookup"><span data-stu-id="f3ac0-130">Remove the service group member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.System#Collections#IEnumerable#GetEnumerator" />
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