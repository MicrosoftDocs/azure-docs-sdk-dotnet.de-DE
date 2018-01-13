<Type Name="DeployedCodePackageList" FullName="System.Fabric.Query.DeployedCodePackageList">
  <TypeSignature Language="C#" Value="public sealed class DeployedCodePackageList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedCodePackage&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedCodePackage&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedCodePackage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedCodePackageList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.DeployedCodePackage&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.DeployedCodePackage&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.DeployedCodePackage&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedCodePackageList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedCodePackageList&#xA;Implements ICollection(Of DeployedCodePackage), IEnumerable(Of DeployedCodePackage), IList(Of DeployedCodePackage)" />
  <TypeSignature Language="F#" Value="type DeployedCodePackageList = class&#xA;    interface IList&lt;DeployedCodePackage&gt;&#xA;    interface ICollection&lt;DeployedCodePackage&gt;&#xA;    interface seq&lt;DeployedCodePackage&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedCodePackage&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedCodePackage&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedCodePackage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>Stellt diese Liste, die geändert werden kann, nur dann, wenn diese Eigenschaft auf "false" festgelegt ist.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Add(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As DeployedCodePackage)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.DeployedCodePackage -&gt; unit&#xA;override this.Add : System.Fabric.Query.DeployedCodePackage -&gt; unit" Usage="deployedCodePackageList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>Das Element hinzugefügt werden.</para>
        </param>
        <summary>
          <para>Fügt das angegebene Element der Liste hinzu.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="deployedCodePackageList.Clear " />
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
          <para>Entfernt alle Elemente aus der Liste.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Contains(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As DeployedCodePackage) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.DeployedCodePackage -&gt; bool&#xA;override this.Contains : System.Fabric.Query.DeployedCodePackage -&gt; bool" Usage="deployedCodePackageList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>Das angegebene Element, das in der Liste enthalten.</para>
        </param>
        <summary>
          <para>Gibt "true" zurück, wenn das angegebene Element in der Liste befindet.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> enthält die Liste das angegebene Element ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.DeployedCodePackage[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.DeployedCodePackage[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.CopyTo(System.Fabric.Query.DeployedCodePackage[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As DeployedCodePackage(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.DeployedCodePackage[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.DeployedCodePackage[] * int -&gt; unit" Usage="deployedCodePackageList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.DeployedCodePackage[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para>Das eindimensionale Array.</para>
        </param>
        <param name="arrayIndex">
          <para>Der Index im Zielarray, ab dem kopiert werden soll.</para>
        </param>
        <summary>
          <para>Kopiert die Elemente aus der Liste in das angegebene Array am angegebenen Index ab.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackageList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.DeployedCodePackageList.Count" />
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
          <para>Ruft ab oder legt einen Wert, der die Anzahl der Elemente in dieser Liste angibt.</para>
        </summary>
        <value>
          <para>Die Anzahl der Elemente in dieser Liste.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.DeployedCodePackage&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of DeployedCodePackage)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt;" Usage="deployedCodePackageList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft einen Enumerator für Elemente in dieser Liste.</para>
        </summary>
        <returns>
          <para>Ein Enumerator für Elemente in dieser Liste </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.IndexOf(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As DeployedCodePackage) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.DeployedCodePackage -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.DeployedCodePackage -&gt; int" Usage="deployedCodePackageList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>Der angegebene Index des Elements.</para>
        </param>
        <summary>
          <para>Ruft den Index des angegebenen Elements in dieser Liste ab.</para>
        </summary>
        <returns>
          <para>Der Index des angegebenen Elements in dieser Liste.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Insert(System.Int32,System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As DeployedCodePackage)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.DeployedCodePackage -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.DeployedCodePackage -&gt; unit" Usage="deployedCodePackageList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>Der nullbasierte Index, an dem das Element eingefügt werden soll.</para>
        </param>
        <param name="item">
          <para>Das Objekt, das in die Liste eingefügt werden soll.</para>
        </param>
        <summary>
          <para>Fügt das Element am angegebenen Index.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackageList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.DeployedCodePackageList.IsReadOnly" />
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
          <para>Ruft ab oder legt einen Wert, der angibt, ob diese Liste geändert werden kann, nur dann, wenn diese Eigenschaft auf "false" festgelegt ist.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> , wenn die Liste nur geändert, andernfalls werden kann <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedCodePackage this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedCodePackage Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackageList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As DeployedCodePackage" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.DeployedCodePackage with get, set" Usage="System.Fabric.Query.DeployedCodePackageList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedCodePackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>Der angegebene Index des Elements.</para>
        </param>
        <summary>
          <para>Ruft das Element am angegebenen Index ab.</para>
        </summary>
        <value>
          <para>Das bereitgestellte Element am angegebenen Index.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Remove(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As DeployedCodePackage) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.DeployedCodePackage -&gt; bool&#xA;override this.Remove : System.Fabric.Query.DeployedCodePackage -&gt; bool" Usage="deployedCodePackageList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>Das Objekt, das aus der Liste entfernt werden soll.</para>
        </param>
        <summary>
          <para>Entfernt das angegebene Element aus dieser Liste.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn das Element erfolgreich aus der Liste entfernt wurde, andernfalls wurde <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="deployedCodePackageList.RemoveAt index" />
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
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para>Ruft einen Enumerator für Elemente in dieser Liste.</para>
        </summary>
        <returns>
          <para>Ein Enumerator für die Elemente in dieser Liste.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>