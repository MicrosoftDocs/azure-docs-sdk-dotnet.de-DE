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
            Stellt einen Batchvorgang für eine Tabelle dar.
            </summary>
    <remarks>
      <para>Ein Batchvorgang ist eine Auflistung von Tabellenvorgängen, die von der Storage-Dienst-REST-API als einzelner atomarischer Vorgang, durch den Aufruf ausgeführt werden ein <a href="http://msdn.microsoft.com/en-us/library/windowsazure/dd894038.aspx">Entitätsgruppentransaktion</a>.</para>
      <para>Ein Batchvorgang kann bis zu 100 einzelne Tabellenvorgänge umfassen, mit der Anforderung enthalten, dass jede vorgangsentität denselben Partitionsschlüssel verfügen muss. Ein Batch mit einem Abrufvorgang darf keine keine anderen Vorgänge enthalten. Beachten Sie, dass die gesamtnutzlast eines Batchvorgangs auf 4 MB beschränkt ist.</para>
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />-Klasse.
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
        <param name="item">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> hinzuzufügende Element der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</param>
        <summary>
            Fügt <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> hinzu.
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
            Löscht alle <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Objekte aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.
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
        <param name="item">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu suchenden Elements.</param>
        <summary>
            Gibt <c>"true"</c> Wenn diese <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> das angegebene Element enthält.
            </summary>
        <returns>
          <c>"true"</c> , wenn das Element, in enthalten ist der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />; <c>"false"</c>, andernfalls.</returns>
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
        <param name="array">Ein eindimensionales Array, das als Ziel für die Elemente kopiert dient der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</param>
        <param name="arrayIndex">Der Index im Zielarray, an dem der Kopiervorgang beginnt.</param>
        <summary>
            Kopiert alle Elemente der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> auf das angegebene eindimensionale Array, beginnend ab dem angegebenen Index im Zielarray. 
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
            Ruft die Anzahl der Vorgänge in diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.
            </summary>
        <value>Die Anzahl der Vorgänge in der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</value>
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
        <param name="entity">Die Entität aus der Tabelle gelöscht werden soll.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die die angegebene Entität aus einer Tabelle löscht.
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
            Gibt einen <see cref="T:System.Collections.Generic.IEnumerator`1" /> für das <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> zurück.
            </summary>
        <returns>Ein <see cref="T:System.Collections.IEnumerator" /> für <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Elemente.</returns>
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
        <param name="item">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu suchenden Elements.</param>
        <summary>
            Gibt den nullbasierten Index des ersten Vorkommens des angegebenen <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element oder -1, wenn die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> enthält das Element nicht.
            </summary>
        <returns>Der nullbasierte Index des ersten Vorkommens des Elements innerhalb der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />, sofern gefunden, andernfalls – 1.</returns>
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
        <param name="entity">Die Entität in der Tabelle eingefügt werden soll.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , der die angegebene Entität in eine Tabelle einfügt.
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
        <param name="entity">Die Entität in der Tabelle eingefügt werden soll.</param>
        <param name="echoContent">
          <c>"true"</c> Wenn die Nachrichtennutzlast, die an die Antwort zum Einfügevorgang zurückgegeben, andernfalls werden soll <c>"false"</c>.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> -Objekt, das die angegebene Entität in der Tabelle als Teil des Batchvorgangs einfügt.
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
        <param name="index">Der Index, an dem Einfügen der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />.</param>
        <param name="item">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> einzufügende Element.</param>
        <summary>
            Fügt am angegebenen Index ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />-Element in die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> ein.
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
        <param name="entity">Die Entität, deren Inhalt, eingefügt oder zusammengeführt werden.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist, wenn die Entität vorhanden ist dann ihre Inhalte mit der angegebenen Entität zusammengeführt.
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
        <param name="entity">Die Entität, deren Inhalt, eingefügt oder ersetzt.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist, wenn die Entität vorhanden ist dann ihre Inhalte durch die angegebene Entität ersetzt.
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
            Ruft einen Wert ab, der angibt, ob das <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> schreibgeschützt ist.
            </summary>
        <value>
          <c>"true"</c> Wenn die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> ist schreibgeschützt. <c>"false"</c>, andernfalls.</value>
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
        <param name="index">Der Index, an dem zum Abrufen oder Festlegen der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element.</param>
        <summary>
            Ruft ab oder legt die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element am angegebenen Index.
            </summary>
        <value>Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element am angegebenen Index.</value>
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
        <param name="entity">Die Entität, deren Inhalt zusammengeführt wird.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die den Inhalt der angegebenen Entität mit der vorhandenen Entität in einer Tabelle zusammenführt.
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
        <param name="item">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> zu entfernenden Elements.</param>
        <summary>
            Entfernt das angegebene <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Element aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.
            </summary>
        <returns>
          <c>"true"</c> , wenn das Element erfolgreich entfernt wurde; <c>"false"</c>, andernfalls.</returns>
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
        <param name="index">Der Index des der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Aufheben der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> am angegebenen Index aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.
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
        <param name="entity">Die Entität, deren Inhalt ersetzt werden.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , die den Inhalt der angegebenen Entität in einer Tabelle ersetzt.
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
        <param name="partitionKey">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</param>
        <param name="rowKey">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> auf die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" /> , der eine Entität mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel abruft.
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
        <typeparam name="TElement">Die Klasse der abzurufende Typ für die Entität.</typeparam>
        <param name="partitionKey">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</param>
        <param name="rowKey">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</param>
        <param name="selectedColumns">Liste der Spaltennamen für die Projektion.</param>
        <summary>
            Fügt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> in den Batch, die eine entitätsbasierten Partitionsschlüssel und Zeilenschlüssel abruft. Die Entität wird in den angegebenen Klassentyp wiederum erweitert deserialisiert werden <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />.
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
        <typeparam name="TResult">Der Rückgabetyp der angegebenen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> die angegebene Entität aufgelöst wird.</typeparam>
        <param name="partitionKey">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</param>
        <param name="rowKey">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</param>
        <param name="resolver">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> -Implementierung zum projizieren der Entität als einen bestimmten Typ im Ergebnis abrufen.</param>
        <param name="selectedColumns">Liste der Spaltennamen für die Projektion.</param>
        <summary>
            Fügt einen tabellenvorgang, um eine Entität des Typs angegebenen Klasse mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel zum Batchvorgang abzurufen.
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
            Gibt einen <see cref="T:System.Collections.IEnumerator" /> zurück.
            </summary>
        <returns>Ein <see cref="T:System.Collections.IEnumerator" /> für das <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>