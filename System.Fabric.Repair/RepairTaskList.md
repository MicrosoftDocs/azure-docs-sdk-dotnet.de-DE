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
      <para>Stellt eine Liste von <see cref="T:System.Fabric.Repair.RepairTask" /> Objekte.</para>
      <para>Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
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
          <para>Das Objekt, das der Liste hinzugefügt werden soll.</para>
        </param>
        <summary>
          <para>Fügt der <see cref="T:System.Fabric.Repair.RepairTaskList" /> ein Element hinzu.</para>
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
          <para>Entfernt alle Elemente aus <see cref="T:System.Fabric.Repair.RepairTaskList" />.</para>
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
          <para>Das Objekt, das in der Liste gesucht werden soll.</para>
        </param>
        <summary>
          <para>Ermittelt, ob die <see cref="T:System.Fabric.Repair.RepairTaskList" /> einen bestimmten Wert enthält.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn die <see cref="T:System.Fabric.Repair.RepairTaskList" /> einen bestimmten Wert enthält, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
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
          <para>Das eindimensionale Array, das das Ziel der aus kopierten Elemente ist <see cref="T:System.Fabric.Repair.RepairTaskList" />. Für das Array muss eine nullbasierte Indizierung verwendet werden.</para>
        </param>
        <param name="arrayIndex">
          <para>Der nullbasierte Index im Array, ab dem kopiert wird.</para>
        </param>
        <summary>
          <para>Kopiert die Elemente der <see cref="T:System.Fabric.Repair.RepairTaskList" /> beginnend an einem bestimmten Arrayindex in ein Array.</para>
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
          <para>Ruft die Anzahl der Elemente ab, die in <see cref="T:System.Fabric.Repair.RepairTaskList" /> enthalten sind.</para>
        </summary>
        <value>
          <para>Die Anzahl der Elemente, die in <see cref="T:System.Fabric.Repair.RepairTaskList" /> enthalten sind.</para>
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
          <para>Gibt einen Enumerator zurück, der die Auflistung durchläuft.</para>
        </summary>
        <returns>
          <para>Ein Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</para>
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
          <para>Das Objekt, das in der Liste gesucht werden soll.</para>
        </param>
        <summary>
          <para>Bestimmt den Index eines bestimmten Elements in der <see cref="T:System.Fabric.Repair.RepairTaskList" />.</para>
        </summary>
        <returns>
          <para>Der Index des Elements Wenn in der Liste gefunden andernfalls -1.</para>
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
          <para>Der nullbasierte Index, an dem das Element eingefügt werden soll.</para>
        </param>
        <param name="item">
          <para>Das Objekt, das in die Liste eingefügt werden soll.</para>
        </param>
        <summary>
          <para>Fügt am angegebenen Index ein Element in die <see cref="T:System.Fabric.Repair.RepairTaskList" /> ein.</para>
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
          <para>Ruft einen Wert ab, der angibt, ob das <see cref="T:System.Fabric.Repair.RepairTaskList" /> schreibgeschützt ist.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn die <see cref="T:System.Fabric.Repair.RepairTaskList" /> schreibgeschützt ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
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
          <para>Der nullbasierte Index des Elements, das abgerufen oder festgelegt werden soll.</para>
        </param>
        <summary>
          <para>Ruft das Element am angegebenen Index ab oder legt dieses fest.</para>
        </summary>
        <value>
          <para>Das Element am angegebenen Index.</para>
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
          <para>Das Objekt, das aus der Liste entfernt werden soll.</para>
        </param>
        <summary>
          <para>Entfernt das erste Vorkommen eines angegebenen Objekts aus der <see cref="T:System.Fabric.Repair.RepairTaskList" />.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn das Element erfolgreich aus der Liste entfernt wurde, andernfalls wurde <languageKeyword>"false"</languageKeyword>. Diese Methode gibt auch "false", wenn das Element nicht in der ursprünglichen Liste gefunden wird.</para>
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
          <para>Der nullbasierte Index des zu entfernenden Elements.</para>
        </param>
        <summary>
          <para>Entfernt das Element am angegebenen Index.</para>
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
          <para>Gibt einen Enumerator zurück, der die Auflistung durchläuft.</para>
        </summary>
        <returns>
          <para>Ein Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>