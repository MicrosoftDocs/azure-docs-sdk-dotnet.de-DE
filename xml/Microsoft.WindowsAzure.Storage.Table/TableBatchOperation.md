<Type Name="TableBatchOperation" FullName="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation">
  <TypeSignature Language="C#" Value="public sealed class TableBatchOperation : System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;, System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;, System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableBatchOperation extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;, class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableBatchOperation&#xA;Implements ICollection(Of TableOperation), IEnumerable(Of TableOperation), IList(Of TableOperation)" />
  <TypeSignature Language="F#" Value="type TableBatchOperation = class&#xA;    interface IList&lt;TableOperation&gt;&#xA;    interface ICollection&lt;TableOperation&gt;&#xA;    interface seq&lt;TableOperation&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5d18d-101">Stellt einen Batchvorgang für eine Tabelle dar.</span><span class="sxs-lookup"><span data-stu-id="5d18d-101">Represents a batch operation on a table.</span></span>
            </summary>
    <remarks>
      <para><span data-ttu-id="5d18d-102">Ein Batchvorgang ist eine Auflistung von Tabellenvorgängen, die von der Storage-Dienst-REST-API als einzelner atomarischer Vorgang, durch den Aufruf ausgeführt werden ein <a href="http://msdn.microsoft.com/en-us/library/windowsazure/dd894038.aspx">Entitätsgruppentransaktion</a>.</span><span class="sxs-lookup"><span data-stu-id="5d18d-102">A batch operation is a collection of table operations which are executed by the Storage Service REST API as a single atomic operation, by invoking an <a href="http://msdn.microsoft.com/en-us/library/windowsazure/dd894038.aspx">Entity Group Transaction</a>.</span></span></para>
      <para><span data-ttu-id="5d18d-103">Ein Batchvorgang kann bis zu 100 einzelne Tabellenvorgänge umfassen, mit der Anforderung enthalten, dass jede vorgangsentität denselben Partitionsschlüssel verfügen muss.</span><span class="sxs-lookup"><span data-stu-id="5d18d-103">A batch operation may contain up to 100 individual table operations, with the requirement that each operation entity must have same partition key.</span></span> <span data-ttu-id="5d18d-104">Ein Batch mit einem Abrufvorgang darf keine keine anderen Vorgänge enthalten.</span><span class="sxs-lookup"><span data-stu-id="5d18d-104">A batch with a retrieve operation cannot contain any other operations.</span></span> <span data-ttu-id="5d18d-105">Beachten Sie, dass die gesamtnutzlast eines Batchvorgangs auf 4 MB beschränkt ist.</span><span class="sxs-lookup"><span data-stu-id="5d18d-105">Note that the total payload of a batch operation is limited to 4MB.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableBatchOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d18d-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5d18d-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (Microsoft.WindowsAzure.Storage.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class Microsoft.WindowsAzure.Storage.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Add(Microsoft.WindowsAzure.Storage.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As TableOperation)" />
      <MemberSignature Language="F#" Value="abstract member Add : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; unit&#xA;override this.Add : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; unit" Usage="tableBatchOperation.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="5d18d-107">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> hinzuzufügende Element der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-107">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item to add to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-108">Fügt <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> hinzu.</span><span class="sxs-lookup"><span data-stu-id="5d18d-108">Adds the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="tableBatchOperation.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d18d-109">Löscht alle <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Objekte aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-109">Clears all <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> objects from the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.WindowsAzure.Storage.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class Microsoft.WindowsAzure.Storage.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Contains(Microsoft.WindowsAzure.Storage.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As TableOperation) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; bool&#xA;override this.Contains : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; bool" Usage="tableBatchOperation.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="5d18d-110">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu suchenden Elements.</span><span class="sxs-lookup"><span data-stu-id="5d18d-110">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item to search for.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-111">Gibt <c>"true"</c> Wenn diese <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> das angegebene Element enthält.</span><span class="sxs-lookup"><span data-stu-id="5d18d-111">Returns <c>true</c> if this <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> contains the specified element.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d18d-112"><c>"true"</c> , wenn das Element, in enthalten ist der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />; <c>"false"</c>, andernfalls.</span><span class="sxs-lookup"><span data-stu-id="5d18d-112"><c>true</c> if the item is contained in the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />; <c>false</c>, otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (Microsoft.WindowsAzure.Storage.Table.TableOperation[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class Microsoft.WindowsAzure.Storage.Table.TableOperation[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.CopyTo(Microsoft.WindowsAzure.Storage.Table.TableOperation[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As TableOperation(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : Microsoft.WindowsAzure.Storage.Table.TableOperation[] * int -&gt; unit&#xA;override this.CopyTo : Microsoft.WindowsAzure.Storage.Table.TableOperation[] * int -&gt; unit" Usage="tableBatchOperation.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="5d18d-113">Ein eindimensionales Array, das als Ziel für die Elemente kopiert dient der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-113">A one-dimensional array that serves as the destination for the elements copied from the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="5d18d-114">Der Index im Zielarray, an dem der Kopiervorgang beginnt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-114">The index in the destination array at which copying begins.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-115">Kopiert alle Elemente der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> auf das angegebene eindimensionale Array, beginnend ab dem angegebenen Index im Zielarray.</span><span class="sxs-lookup"><span data-stu-id="5d18d-115">Copies all the elements of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> to the specified one-dimensional array starting at the specified destination array index.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d18d-116">Ruft die Anzahl der Vorgänge in diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-116">Gets the number of operations in this <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span>
            </summary>
        <value><span data-ttu-id="5d18d-117">Die Anzahl der Vorgänge in der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-117">The number of operations in the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Delete(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Delete : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Delete entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5d18d-118">Die Entität aus der Tabelle gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d18d-118">The entity to be deleted from the table.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-119">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die die angegebene Entität aus einer Tabelle löscht.</span><span class="sxs-lookup"><span data-stu-id="5d18d-119">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> that deletes the specified entity from a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableOperation&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of TableOperation)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;" Usage="tableBatchOperation.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.TableOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d18d-120">Gibt einen <see cref="T:System.Collections.Generic.IEnumerator`1" /> für das <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="5d18d-120">Returns an <see cref="T:System.Collections.Generic.IEnumerator`1" /> for the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span>
            </summary>
        <returns><span data-ttu-id="5d18d-121">Ein <see cref="T:System.Collections.IEnumerator" /> für <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Elemente.</span><span class="sxs-lookup"><span data-stu-id="5d18d-121">An <see cref="T:System.Collections.IEnumerator" /> for <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> items.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (Microsoft.WindowsAzure.Storage.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class Microsoft.WindowsAzure.Storage.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.IndexOf(Microsoft.WindowsAzure.Storage.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As TableOperation) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; int&#xA;override this.IndexOf : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; int" Usage="tableBatchOperation.IndexOf item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.IndexOf(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="5d18d-122">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu suchenden Elements.</span><span class="sxs-lookup"><span data-stu-id="5d18d-122">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item to search for.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-123">Gibt den nullbasierten Index des ersten Vorkommens des angegebenen <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element oder -1, wenn die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> enthält das Element nicht.</span><span class="sxs-lookup"><span data-stu-id="5d18d-123">Returns the zero-based index of the first occurrence of the specified <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item, or -1 if the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> does not contain the item.</span></span>
            </summary>
        <returns><span data-ttu-id="5d18d-124">Der nullbasierte Index des ersten Vorkommens des Elements innerhalb der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />, sofern gefunden, andernfalls – 1.</span><span class="sxs-lookup"><span data-stu-id="5d18d-124">The zero-based index of the first occurrence of item within the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />, if found; otherwise, –1.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Insert(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Insert(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Insert : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Insert entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5d18d-125">Die Entität in der Tabelle eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d18d-125">The entity to be inserted into the table.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-126">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , der die angegebene Entität in eine Tabelle einfügt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-126">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> that inserts the specified entity into a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity, bool echoContent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Insert(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity, bool echoContent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Insert(Microsoft.WindowsAzure.Storage.Table.ITableEntity,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (entity As ITableEntity, echoContent As Boolean)" />
      <MemberSignature Language="F#" Value="member this.Insert : Microsoft.WindowsAzure.Storage.Table.ITableEntity * bool -&gt; unit" Usage="tableBatchOperation.Insert (entity, echoContent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
        <Parameter Name="echoContent" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5d18d-127">Die Entität in der Tabelle eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d18d-127">The entity to be inserted into the table.</span></span></param>
        <param name="echoContent">
          <span data-ttu-id="5d18d-128"><c>"true"</c> Wenn die Nachrichtennutzlast, die an die Antwort zum Einfügevorgang zurückgegeben, andernfalls werden soll <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="5d18d-128"><c>true</c> if the message payload should be returned in the response to the insert operation;otherwise, <c>false</c>.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-129">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> -Objekt, das die angegebene Entität in der Tabelle als Teil des Batchvorgangs einfügt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-129">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object that inserts the specified entity into the table as part of the batch operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, Microsoft.WindowsAzure.Storage.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class Microsoft.WindowsAzure.Storage.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Insert(System.Int32,Microsoft.WindowsAzure.Storage.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As TableOperation)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; unit&#xA;override this.Insert : int * Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; unit" Usage="tableBatchOperation.Insert (index, item)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.Insert(System.Int32,`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="item" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="5d18d-130">Der Index, an dem Einfügen der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-130">The index at which to insert the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />.</span></span></param>
        <param name="item"><span data-ttu-id="5d18d-131">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> einzufügende Element.</span><span class="sxs-lookup"><span data-stu-id="5d18d-131">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item to insert.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-132">Fügt am angegebenen Index ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />-Element in die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> ein.</span><span class="sxs-lookup"><span data-stu-id="5d18d-132">Inserts a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> into the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> at the specified index.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrMerge">
      <MemberSignature Language="C#" Value="public void InsertOrMerge (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void InsertOrMerge(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.InsertOrMerge(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub InsertOrMerge (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.InsertOrMerge : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.InsertOrMerge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5d18d-133">Die Entität, deren Inhalt, eingefügt oder zusammengeführt werden.</span><span class="sxs-lookup"><span data-stu-id="5d18d-133">The entity whose contents are being inserted or merged.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-134">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist, wenn die Entität vorhanden ist dann ihre Inhalte mit der angegebenen Entität zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-134">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> that inserts the specified entity into a table if the entity does not exist; if the entity does exist then its contents are merged with the provided entity.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrReplace">
      <MemberSignature Language="C#" Value="public void InsertOrReplace (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void InsertOrReplace(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.InsertOrReplace(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub InsertOrReplace (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.InsertOrReplace : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.InsertOrReplace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5d18d-135">Die Entität, deren Inhalt, eingefügt oder ersetzt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-135">The entity whose contents are being inserted or replaced.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-136">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist, wenn die Entität vorhanden ist dann ihre Inhalte durch die angegebene Entität ersetzt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-136">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> that inserts the specified entity into a table if the entity does not exist; if the entity does exist then its contents are replaced with the provided entity.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d18d-137">Ruft einen Wert ab, der angibt, ob das <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> schreibgeschützt ist.</span><span class="sxs-lookup"><span data-stu-id="5d18d-137">Gets a value indicating whether the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> is read-only.</span></span>
            </summary>
        <value>
          <span data-ttu-id="5d18d-138"><c>"true"</c> Wenn die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> ist schreibgeschützt. <c>"false"</c>, andernfalls.</span><span class="sxs-lookup"><span data-stu-id="5d18d-138"><c>true</c> if the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> is read-only; <c>false</c>, otherwise.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableOperation this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.TableOperation Item(int32)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As TableOperation" />
      <MemberSignature Language="F#" Value="member this.Item(int) : Microsoft.WindowsAzure.Storage.Table.TableOperation with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="5d18d-139">Der Index, an dem zum Abrufen oder Festlegen der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element.</span><span class="sxs-lookup"><span data-stu-id="5d18d-139">The index at which to get or set the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-140">Ruft ab oder legt die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="5d18d-140">Gets or sets the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item at the specified index.</span></span>
            </summary>
        <value><span data-ttu-id="5d18d-141">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="5d18d-141">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item at the specified index.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public void Merge (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Merge(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Merge(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Merge (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Merge : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Merge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5d18d-142">Die Entität, deren Inhalt zusammengeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5d18d-142">The entity whose contents are being merged.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-143">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die den Inhalt der angegebenen Entität mit der vorhandenen Entität in einer Tabelle zusammenführt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-143">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> that merges the contents of the specified entity with the existing entity in a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (Microsoft.WindowsAzure.Storage.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class Microsoft.WindowsAzure.Storage.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Remove(Microsoft.WindowsAzure.Storage.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As TableOperation) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; bool&#xA;override this.Remove : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; bool" Usage="tableBatchOperation.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="5d18d-144">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="5d18d-144">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item to remove.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-145">Entfernt das angegebene <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-145">Removes the specified <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> item from the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="5d18d-146"><c>"true"</c> , wenn das Element erfolgreich entfernt wurde; <c>"false"</c>, andernfalls.</span><span class="sxs-lookup"><span data-stu-id="5d18d-146"><c>true</c> if the item was successfully removed; <c>false</c>, otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="tableBatchOperation.RemoveAt index" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.RemoveAt(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="5d18d-147">Der Index des der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Aufheben der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-147">The index of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to remove from the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-148">Entfernt die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> am angegebenen Index aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-148">Removes the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> at the specified index from the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="public void Replace (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Replace(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Replace(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Replace (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Replace : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Replace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5d18d-149">Die Entität, deren Inhalt ersetzt werden.</span><span class="sxs-lookup"><span data-stu-id="5d18d-149">The entity whose contents are being replaced.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-150">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die den Inhalt der angegebenen Entität in einer Tabelle ersetzt.</span><span class="sxs-lookup"><span data-stu-id="5d18d-150">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> that replaces the contents of the specified entity in a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve">
      <MemberSignature Language="C#" Value="public void Retrieve (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retrieve(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Retrieve(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retrieve (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="member this.Retrieve : string * string -&gt; unit" Usage="tableBatchOperation.Retrieve (partitionKey, rowKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="5d18d-151">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="5d18d-151">A string containing the partition key of the entity to retrieve.</span></span></param>
        <param name="rowKey"><span data-ttu-id="5d18d-152">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="5d18d-152">A string containing the row key of the entity to retrieve.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-153">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , der eine Entität mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel abruft.</span><span class="sxs-lookup"><span data-stu-id="5d18d-153">Adds a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> to the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> that retrieves an entity with the specified partition key and row key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public void Retrieve&lt;TElement&gt; (string partitionKey, string rowKey, System.Collections.Generic.List&lt;string&gt; selectedColumns = null) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntity;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retrieve&lt;(class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(string partitionKey, string rowKey, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Retrieve``1(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retrieve(Of TElement As ITableEntity) (partitionKey As String, rowKey As String, Optional selectedColumns As List(Of String) = null)" />
      <MemberSignature Language="F#" Value="member this.Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; unit (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity)" Usage="tableBatchOperation.Retrieve (partitionKey, rowKey, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="5d18d-154">Die Klasse der abzurufende Typ für die Entität.</span><span class="sxs-lookup"><span data-stu-id="5d18d-154">The class of type for the entity to retrieve.</span></span></typeparam>
        <param name="partitionKey"><span data-ttu-id="5d18d-155">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="5d18d-155">A string containing the partition key of the entity to retrieve.</span></span></param>
        <param name="rowKey"><span data-ttu-id="5d18d-156">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="5d18d-156">A string containing the row key of the entity to retrieve.</span></span></param>
        <param name="selectedColumns"><span data-ttu-id="5d18d-157">Liste der Spaltennamen für die Projektion.</span><span class="sxs-lookup"><span data-stu-id="5d18d-157">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-158">Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> in den Batch, die eine entitätsbasierten Partitionsschlüssel und Zeilenschlüssel abruft.</span><span class="sxs-lookup"><span data-stu-id="5d18d-158">Inserts a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> into the batch that retrieves an entity based on its row key and partition key.</span></span> <span data-ttu-id="5d18d-159">Die Entität wird in den angegebenen Klassentyp wiederum erweitert deserialisiert werden <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-159">The entity will be deserialized into the specified class type which extends <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public void Retrieve&lt;TResult&gt; (string partitionKey, string rowKey, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retrieve&lt;TResult&gt;(string partitionKey, string rowKey, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.Retrieve``1(System.String,System.String,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retrieve(Of TResult) (partitionKey As String, rowKey As String, resolver As EntityResolver(Of TResult), Optional selectedColumns As List(Of String) = null)" />
      <MemberSignature Language="F#" Value="member this.Retrieve : string * string * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * System.Collections.Generic.List&lt;string&gt; -&gt; unit" Usage="tableBatchOperation.Retrieve (partitionKey, rowKey, resolver, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="5d18d-160">Der Rückgabetyp der angegebenen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> die angegebene Entität aufgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="5d18d-160">The return type which the specified <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> will resolve the given entity to.</span></span></typeparam>
        <param name="partitionKey"><span data-ttu-id="5d18d-161">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="5d18d-161">A string containing the partition key of the entity to retrieve.</span></span></param>
        <param name="rowKey"><span data-ttu-id="5d18d-162">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="5d18d-162">A string containing the row key of the entity to retrieve.</span></span></param>
        <param name="resolver"><span data-ttu-id="5d18d-163">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> -Implementierung zum projizieren der Entität als einen bestimmten Typ im Ergebnis abrufen.</span><span class="sxs-lookup"><span data-stu-id="5d18d-163">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> implementation to project the entity to retrieve as a particular type in the result.</span></span></param>
        <param name="selectedColumns"><span data-ttu-id="5d18d-164">Liste der Spaltennamen für die Projektion.</span><span class="sxs-lookup"><span data-stu-id="5d18d-164">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="5d18d-165">Fügt einen tabellenvorgang, um eine Entität des Typs angegebenen Klasse mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel zum Batchvorgang abzurufen.</span><span class="sxs-lookup"><span data-stu-id="5d18d-165">Adds a table operation to retrieve an entity of the specified class type with the specified partition key and row key to the batch operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d18d-166">Gibt einen <see cref="T:System.Collections.IEnumerator" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="5d18d-166">Returns an <see cref="T:System.Collections.IEnumerator" />.</span></span>
            </summary>
        <returns><span data-ttu-id="5d18d-167">Ein <see cref="T:System.Collections.IEnumerator" /> für das <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="5d18d-167">An <see cref="T:System.Collections.IEnumerator" /> for the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>