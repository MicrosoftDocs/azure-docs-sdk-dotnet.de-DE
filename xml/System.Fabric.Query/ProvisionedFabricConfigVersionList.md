<Type Name="ProvisionedFabricConfigVersionList" FullName="System.Fabric.Query.ProvisionedFabricConfigVersionList">
  <TypeSignature Language="C#" Value="public sealed class ProvisionedFabricConfigVersionList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ProvisionedFabricConfigVersionList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ProvisionedFabricConfigVersionList&#xA;Implements ICollection(Of ProvisionedFabricConfigVersion), IEnumerable(Of ProvisionedFabricConfigVersion), IList(Of ProvisionedFabricConfigVersion)" />
  <TypeSignature Language="F#" Value="type ProvisionedFabricConfigVersionList = class&#xA;    interface IList&lt;ProvisionedFabricConfigVersion&gt;&#xA;    interface ICollection&lt;ProvisionedFabricConfigVersion&gt;&#xA;    interface seq&lt;ProvisionedFabricConfigVersion&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="3cd01-101">Stellt die Liste der bereitgestellten Service Fabric-Konfiguration (Cluster-Manifest)-Versionen, die durch den Aufruf abgerufen <see cref="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="3cd01-101">Represents the list of provisioned Service Fabric configuration (Cluster Manifest) versions retrieved by calling <see cref="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Add(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit&#xA;override this.Add : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit" Usage="provisionedFabricConfigVersionList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3cd01-102">Das angegebene Element in der Liste hinzu.</span><span class="sxs-lookup"><span data-stu-id="3cd01-102">The specified item to add in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-103">Fügt das angegebene Element zu dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-103">Adds the specified item to this list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="provisionedFabricConfigVersionList.Clear " />
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
          <para><span data-ttu-id="3cd01-104">Entfernt alle Elemente aus dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-104">Removes all items from this list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Contains(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ProvisionedFabricConfigVersion) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool" Usage="provisionedFabricConfigVersionList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3cd01-105">Das angegebene Element, das in der Liste enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="3cd01-105">The specified item that is contained in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-106">Gibt "true" zurück, wenn das angegebene Element in dieser Liste enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="3cd01-106">Returns true if the specified item is contained in this list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="3cd01-107"><languageKeyword>"true"</languageKeyword> , wenn das angegebene Element in dieser Liste enthalten ist; andernfalls ist <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="3cd01-107"><languageKeyword>true</languageKeyword> if the specified item is contained in this list; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ProvisionedFabricConfigVersion[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ProvisionedFabricConfigVersion[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.CopyTo(System.Fabric.Query.ProvisionedFabricConfigVersion[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ProvisionedFabricConfigVersion(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ProvisionedFabricConfigVersion[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ProvisionedFabricConfigVersion[] * int -&gt; unit" Usage="provisionedFabricConfigVersionList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ProvisionedFabricConfigVersion[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="3cd01-108">Das eindimensionale Array, das das Ziel der aus kopierten Elemente ist <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span><span class="sxs-lookup"><span data-stu-id="3cd01-108">The one-dimensional array that is the destination of elements copied from <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span></span> <span data-ttu-id="3cd01-109">Für das Array muss eine nullbasierte Indizierung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3cd01-109">The array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="3cd01-110">Der nullbasierte Index im Array, ab dem kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="3cd01-110">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-111">Kopiert die Elemente aus dieser Liste in das angegebene Array am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="3cd01-111">Copies items from this list to the specified array at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricConfigVersionList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ProvisionedFabricConfigVersionList.Count" />
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
          <para><span data-ttu-id="3cd01-112">Ruft die Anzahl der Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-112">Gets the number of items in this list.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3cd01-113">Die Anzahl der Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-113">The number of items in this list.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;" Usage="provisionedFabricConfigVersionList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="3cd01-114">Gibt einen Enumerator zurück, auf die Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-114">Returns an enumerator to the items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="3cd01-115">Ein Enumerator für die Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-115">An enumerator to the items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.IndexOf(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ProvisionedFabricConfigVersion) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; int" Usage="provisionedFabricConfigVersionList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3cd01-116">Das angegebene Element in der Liste gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="3cd01-116">The specified item to locate in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-117">Gibt den Index des angegebenen Elements in dieser Liste zurück.</span><span class="sxs-lookup"><span data-stu-id="3cd01-117">Returns the index of the specified item in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="3cd01-118">Der Index des angegebenen Elements in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-118">The index of the specified item in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Insert(System.Int32,System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit" Usage="provisionedFabricConfigVersionList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="3cd01-119">Der nullbasierte Index, an dem das Element eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="3cd01-119">The zero-based index at which item should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="3cd01-120">Das Objekt, das in die Liste eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="3cd01-120">The object to insert into the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-121">Fügt das angegebene Element in dieser Liste am angegebenen Index ein.</span><span class="sxs-lookup"><span data-stu-id="3cd01-121">Inserts the specified item into this list at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricConfigVersionList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ProvisionedFabricConfigVersionList.IsReadOnly" />
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
          <para><span data-ttu-id="3cd01-122">Ruft einen Wert, der angibt, ob die Liste geändert werden kann, nur dann, wenn diese Eigenschaft auf "false" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="3cd01-122">Gets a value that indicates whether the list can be modified only if this property is false.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="3cd01-123"><languageKeyword>"true"</languageKeyword> Wenn die Liste kann, andernfalls geändert werden <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="3cd01-123"><languageKeyword>true</languageKeyword> if the list can be modified only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ProvisionedFabricConfigVersion this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ProvisionedFabricConfigVersion Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricConfigVersionList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ProvisionedFabricConfigVersion" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ProvisionedFabricConfigVersion with get, set" Usage="System.Fabric.Query.ProvisionedFabricConfigVersionList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ProvisionedFabricConfigVersion</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="3cd01-124">Der angegebene Index.</span><span class="sxs-lookup"><span data-stu-id="3cd01-124">The specified index.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-125">Ruft das Element am angegebenen Index ab.</span><span class="sxs-lookup"><span data-stu-id="3cd01-125">Gets the item at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3cd01-126">Das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="3cd01-126">The item at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Remove(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ProvisionedFabricConfigVersion) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool" Usage="provisionedFabricConfigVersionList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="3cd01-127">Das Objekt, das aus der Liste entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="3cd01-127">The object to remove from the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-128">Entfernt das angegebene Element aus dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-128">Removes the specified item from this list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="3cd01-129"><languageKeyword>"true"</languageKeyword> Wenn das Element erfolgreich aus der Liste entfernt wurde, andernfalls wurde <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="3cd01-129"><languageKeyword>true</languageKeyword> if the item was successfully removed from the list; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="provisionedFabricConfigVersionList.RemoveAt index" />
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
          <para><span data-ttu-id="3cd01-130">Der nullbasierte Index des zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="3cd01-130">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3cd01-131">Entfernt das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="3cd01-131">Removes the item from the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="3cd01-132">Ruft einen Enumerator für die Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-132">Gets an enumerator to the items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="3cd01-133">Ein Enumerator für die Elemente in dieser Liste.</span><span class="sxs-lookup"><span data-stu-id="3cd01-133">An enumerator to the items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>