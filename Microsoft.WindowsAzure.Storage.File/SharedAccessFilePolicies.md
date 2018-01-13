<Type Name="SharedAccessFilePolicies" FullName="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessFilePolicies : System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;, System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessFilePolicies extends System.Object implements class System.Collections.Generic.ICollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessFilePolicies&#xA;Implements ICollection(Of KeyValuePair(Of String, SharedAccessFilePolicy)), IDictionary(Of String, SharedAccessFilePolicy), IEnumerable(Of KeyValuePair(Of String, SharedAccessFilePolicy))" />
  <TypeSignature Language="F#" Value="type SharedAccessFilePolicies = class&#xA;    interface IDictionary&lt;string, SharedAccessFilePolicy&gt;&#xA;    interface ICollection&lt;KeyValuePair&lt;string, SharedAccessFilePolicy&gt;&gt;&#xA;    interface seq&lt;KeyValuePair&lt;string, SharedAccessFilePolicy&gt;&gt;&#xA;    interface IEnumerable" />
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
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt die Auflistung der freigegebenen Zugriffsrichtlinien für eine Freigabe definiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessFilePolicies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Add(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As KeyValuePair(Of String, SharedAccessFilePolicy))" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; unit&#xA;override this.Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; unit" Usage="sharedAccessFilePolicies.Add item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item">Die <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, das mit einem Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Wert-Paar, Auflistung der freigegebenen Zugriffsrichtlinien hinzu.</param>
        <summary>
            Fügt den angegebenen Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> in gespeicherten Wert einen <see cref="T:System.Collections.Generic.KeyValuePair`2" />, auf die Auflistung der freigegebenen Zugriffsrichtlinien.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string key, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(string key, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Add(System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (key As String, value As SharedAccessFilePolicy)" />
      <MemberSignature Language="F#" Value="abstract member Add : string * Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy -&gt; unit&#xA;override this.Add : string * Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy -&gt; unit" Usage="sharedAccessFilePolicies.Add (key, value)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.Add(`0,`1)</InterfaceMember>
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
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel des der <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> zu addierende Wert.</param>
        <param name="value">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> SAS-Richtlinien für die Auflistung der hinzuzufügende Wert.</param>
        <summary>
            Fügt den angegebenen Schlüssel und <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Wert auf die Auflistung der freigegebenen Zugriffsrichtlinien.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="sharedAccessFilePolicies.Clear " />
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
            Entfernt sämtliche Schlüssel und <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Werte aus der SAS-Auflistung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Contains(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As KeyValuePair(Of String, SharedAccessFilePolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool&#xA;override this.Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool" Usage="sharedAccessFilePolicies.Contains item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item">Ein <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, das den Schlüssel enthält und <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> zu suchende Wert.</param>
        <summary>
            Bestimmt, ob die Auflistung der freigegebenen Zugriffsrichtlinien den Schlüssel enthält und <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Wert im angegebenen <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt.
            </summary>
        <returns>
          <c>"true"</c> , wenn die Auflistung der freigegebenen Zugriffsrichtlinien den angegebenen Schlüssel/Wert enthält, andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsKey">
      <MemberSignature Language="C#" Value="public bool ContainsKey (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ContainsKey(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.ContainsKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKey (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ContainsKey : string -&gt; bool&#xA;override this.ContainsKey : string -&gt; bool" Usage="sharedAccessFilePolicies.ContainsKey key" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.ContainsKey(`0)</InterfaceMember>
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
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Die in der Auflistung der freigegebenen Zugriffsrichtlinien zu suchende Schlüssel.</param>
        <summary>
            Bestimmt, ob die Auflistung der freigegebenen Zugriffsrichtlinien den angegebenen Schlüssel enthält.
            </summary>
        <returns>
          <c>"true"</c> , wenn die Auflistung der freigegebenen Zugriffsrichtlinien ein Element mit dem angegebenen Schlüssel enthält, andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.CopyTo(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy}[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As KeyValuePair(Of String, SharedAccessFilePolicy)(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] * int -&gt; unit&#xA;override this.CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] * int -&gt; unit" Usage="sharedAccessFilePolicies.CopyTo (array, arrayIndex)" />
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
        <Parameter Name="array" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">Ein eindimensionales Array von <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> -Objekten, fungiert als Ziel für die Elemente aus der Auflistung der freigegebenen Zugriffsrichtlinien kopiert.</param>
        <param name="arrayIndex">Der nullbasierte Index im <paramref name="array" />, bei dem der Kopiervorgang beginnt.</param>
        <summary>
            Kopiert jeden Schlüssel im Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Wert-Paar in ein kompatibles eindimensionales Array, beginnend am angegebenen Index des Zielarrays.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Count" />
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
            Ruft die Anzahl von Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> -Wert-Paare in der Auflistung der freigegebenen Zugriffsrichtlinien.
            </summary>
        <value>Die Anzahl der Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> -Wert-Paare in der Auflistung der freigegebenen Zugriffsrichtlinien.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of KeyValuePair(Of String, SharedAccessFilePolicy))" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;" Usage="sharedAccessFilePolicies.GetEnumerator " />
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
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt einen Enumerator, der die Auflistung der freigegebenen Zugriffsrichtlinien durchläuft.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerator`1" /> vom Typ <see cref="T:System.Collections.Generic.KeyValuePair`2" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.IsReadOnly" />
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
            Ruft einen Wert, der angibt, ob die Auflistung der freigegebenen Zugriffsrichtlinien schreibgeschützt ist. 
            </summary>
        <value>
          <c>"true"</c> Wenn die Auflistung der freigegebenen Zugriffsrichtlinien schreibgeschützt ist, andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As SharedAccessFilePolicy" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Item(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Eine Zeichenfolge, die mit dem Schlüssel des der <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Wert zum Abrufen oder festlegen.</param>
        <summary>
            Ruft ab oder legt die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> mit dem angegebenen Schlüssel zugeordnete Element.
            </summary>
        <value>Die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> mit dem angegebenen Schlüssel zugeordnete Element oder <c>null</c> Wenn Schlüssel nicht in die Auflistung der freigegebenen Zugriffsrichtlinien befindet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;string&gt; Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;string&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Keys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Keys As ICollection(Of String)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.ICollection&lt;string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Keys" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Keys</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Auflistung mit den Schlüsseln in der Auflistung der freigegebenen Zugriffsrichtlinien ab.
            </summary>
        <value>Eine Auflistung von Zeichenfolgen, die mit den Schlüsseln der Auflistung der freigegebenen Zugriffsrichtlinien.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Remove(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As KeyValuePair(Of String, SharedAccessFilePolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool&#xA;override this.Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool" Usage="sharedAccessFilePolicies.Remove item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item">Die <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, das mit einem Schlüssel und <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Wert aus der Auflistung der freigegebenen Zugriffsrichtlinien zu entfernen.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> in angegebener Wert der <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, aus der Auflistung der freigegebenen Zugriffsrichtlinien.
            </summary>
        <returns>
          <c>"true"</c> , wenn das Element erfolgreich entfernt; andernfalls wurde, <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Remove(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : string -&gt; bool&#xA;override this.Remove : string -&gt; bool" Usage="sharedAccessFilePolicies.Remove key" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.Remove(`0)</InterfaceMember>
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
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Eine Zeichenfolge, die mit dem Schlüssel des der <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> zu entfernenden Elements.</param>
        <summary>
            Entfernt den Wert mit dem angegebenen Schlüssel aus der Auflistung der freigegebenen Zugriffsrichtlinien.
            </summary>
        <returns>
          <c>"true"</c> Wenn das Element erfolgreich gefunden und entfernt wurde, andernfalls <c>"false"</c>. Diese Methode gibt <c>"false"</c> , wenn der Schlüssel nicht gefunden wurde.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.System#Collections#IEnumerable#GetEnumerator" />
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
            Gibt einen Enumerator, der die Auflistung der freigegebenen Zugriffsrichtlinien durchläuft.
            </summary>
        <returns>Ein <see cref="T:System.Collections.IEnumerator" /> -Objekt, das verwendet werden kann, zum Durchlaufen der Auflistung der freigegebenen Zugriffsrichtlinien.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public bool TryGetValue (string key, out Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetValue(string key, [out] class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&amp; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.TryGetValue(System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValue (key As String, ByRef value As SharedAccessFilePolicy) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetValue : string *  -&gt; bool&#xA;override this.TryGetValue : string *  -&gt; bool" Usage="sharedAccessFilePolicies.TryGetValue (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key">Eine Zeichenfolge mit dem Schlüssel des abzurufenden Werts.</param>
        <param name="value">Die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> abzurufenden Elements.</param>
        <summary>
            Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> mit dem angegebenen Schlüssel zugeordnete Element. 
            </summary>
        <returns>Die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Element mit dem angegebenen Schlüssel zugeordnet ist, wenn es sich bei der Schlüssel gefunden wurde; andernfalls der Standardwert für die <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Typ.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As ICollection(Of SharedAccessFilePolicy)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Values" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Values</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Auflistung mit den Werten in der Auflistung der freigegebenen Zugriffsrichtlinien ab.
            </summary>
        <value>Eine Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> Elemente in der Auflistung der freigegebenen Zugriffsrichtlinien.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>