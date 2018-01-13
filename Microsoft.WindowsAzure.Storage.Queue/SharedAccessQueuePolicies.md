<Type Name="SharedAccessQueuePolicies" FullName="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessQueuePolicies : System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;, System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessQueuePolicies extends System.Object implements class System.Collections.Generic.ICollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessQueuePolicies&#xA;Implements ICollection(Of KeyValuePair(Of String, SharedAccessQueuePolicy)), IDictionary(Of String, SharedAccessQueuePolicy), IEnumerable(Of KeyValuePair(Of String, SharedAccessQueuePolicy))" />
  <TypeSignature Language="F#" Value="type SharedAccessQueuePolicies = class&#xA;    interface IDictionary&lt;string, SharedAccessQueuePolicy&gt;&#xA;    interface ICollection&lt;KeyValuePair&lt;string, SharedAccessQueuePolicy&gt;&gt;&#xA;    interface seq&lt;KeyValuePair&lt;string, SharedAccessQueuePolicy&gt;&gt;&#xA;    interface IEnumerable" />
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
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="64f9b-101">Stellt die Auflistung der freigegebenen Zugriffsrichtlinien für eine Warteschlange definiert.</span><span class="sxs-lookup"><span data-stu-id="64f9b-101">Represents the collection of shared access policies defined for a queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessQueuePolicies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.#ctor" />
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
      <MemberSignature Language="C#" Value="public void Add (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Add(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As KeyValuePair(Of String, SharedAccessQueuePolicy))" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; -&gt; unit&#xA;override this.Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; -&gt; unit" Usage="sharedAccessQueuePolicies.Add item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="64f9b-102">Die <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, das mit einem Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Wert-Paar, Auflistung der freigegebenen Zugriffsrichtlinien hinzu.</span><span class="sxs-lookup"><span data-stu-id="64f9b-102">The <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object, containing a key/<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value pair, to add to the shared access policies collection.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-103">Fügt den angegebenen Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> in gespeicherten Wert einen <see cref="T:System.Collections.Generic.KeyValuePair`2" />, auf die Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-103">Adds the specified key/<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value, stored in a <see cref="T:System.Collections.Generic.KeyValuePair`2" />, to the collection of shared access policies.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string key, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(string key, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Add(System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (key As String, value As SharedAccessQueuePolicy)" />
      <MemberSignature Language="F#" Value="abstract member Add : string * Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy -&gt; unit&#xA;override this.Add : string * Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy -&gt; unit" Usage="sharedAccessQueuePolicies.Add (key, value)" />
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
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="64f9b-104">Eine Zeichenfolge, die mit dem Schlüssel des der <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> zu addierende Wert.</span><span class="sxs-lookup"><span data-stu-id="64f9b-104">A string containing the key of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value to add.</span></span></param>
        <param name="value"><span data-ttu-id="64f9b-105">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> SAS-Richtlinien für die Auflistung der hinzuzufügende Wert.</span><span class="sxs-lookup"><span data-stu-id="64f9b-105">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value to add the collection of shared access policies.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-106">Fügt den angegebenen Schlüssel und <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Wert auf die Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-106">Adds the specified key and <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value to the collection of shared access policies.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="sharedAccessQueuePolicies.Clear " />
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
            <span data-ttu-id="64f9b-107">Entfernt sämtliche Schlüssel und <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Werte aus der SAS-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="64f9b-107">Removes all keys and <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> values from the shared access collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Contains(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As KeyValuePair(Of String, SharedAccessQueuePolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; -&gt; bool&#xA;override this.Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; -&gt; bool" Usage="sharedAccessQueuePolicies.Contains item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="64f9b-108">Ein <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, das den Schlüssel enthält und <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> zu suchende Wert.</span><span class="sxs-lookup"><span data-stu-id="64f9b-108">A <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object containing the key and <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value to search for.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-109">Bestimmt, ob die Auflistung der freigegebenen Zugriffsrichtlinien den Schlüssel enthält und <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Wert im angegebenen <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="64f9b-109">Determines whether the collection of shared access policies contains the key and <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value in the specified <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="64f9b-110"><c>"true"</c> , wenn die Auflistung der freigegebenen Zugriffsrichtlinien den angegebenen Schlüssel/Wert enthält, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="64f9b-110"><c>true</c> if the shared access policies collection contains the specified key/value; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsKey">
      <MemberSignature Language="C#" Value="public bool ContainsKey (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ContainsKey(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.ContainsKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKey (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ContainsKey : string -&gt; bool&#xA;override this.ContainsKey : string -&gt; bool" Usage="sharedAccessQueuePolicies.ContainsKey key" />
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
        <param name="key"><span data-ttu-id="64f9b-111">Eine Zeichenfolge mit der in der Auflistung der freigegebenen Zugriffsrichtlinien zu suchende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="64f9b-111">A string containing the key to locate in the collection of shared access policies.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-112">Bestimmt, ob die Auflistung der freigegebenen Zugriffsrichtlinien den angegebenen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="64f9b-112">Determines whether the collection of shared access policies contains the specified key.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="64f9b-113"><c>"true"</c> , wenn die Auflistung der freigegebenen Zugriffsrichtlinien ein Element mit dem angegebenen Schlüssel enthält, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="64f9b-113"><c>true</c> if the collection of shared access policies contains an element with the specified key; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.CopyTo(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy}[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As KeyValuePair(Of String, SharedAccessQueuePolicy)(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;[] * int -&gt; unit&#xA;override this.CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;[] * int -&gt; unit" Usage="sharedAccessQueuePolicies.CopyTo (array, arrayIndex)" />
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
        <Parameter Name="array" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="64f9b-114">Ein eindimensionales Array von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> -Objekten, fungiert als Ziel für die Elemente aus der Auflistung der freigegebenen Zugriffsrichtlinien kopiert.</span><span class="sxs-lookup"><span data-stu-id="64f9b-114">A one-dimensional array of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> objects that serves as the destination for the elements copied from the shared access policies collection.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="64f9b-115">Der nullbasierte Index im <paramref name="array" />, bei dem der Kopiervorgang beginnt.</span><span class="sxs-lookup"><span data-stu-id="64f9b-115">The zero-based index in <paramref name="array" /> at which copying begins.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-116">Kopiert jedes Schlüssel-/<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Wert-Paar in der Auflistung der freigegebenen Zugriffsrichtlinien in ein kompatibles eindimensionales Array, beginnend am angegebenen Index des Zielarrays.</span><span class="sxs-lookup"><span data-stu-id="64f9b-116">Copies each key/<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value pair in the shared access policies collection to a compatible one-dimensional array, starting at the specified index of the target array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Count" />
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
            <span data-ttu-id="64f9b-117">Ruft die Anzahl von Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> -Wert-Paare in der Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-117">Gets the number of key/<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value pairs contained in the shared access policies collection.</span></span>
            </summary>
        <value><span data-ttu-id="64f9b-118">Die Anzahl der Schlüssel /<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> -Wert-Paare in der Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-118">The number of key/<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value pairs contained in the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of KeyValuePair(Of String, SharedAccessQueuePolicy))" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;" Usage="sharedAccessQueuePolicies.GetEnumerator " />
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
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="64f9b-119">Gibt einen Enumerator, der die Auflistung der freigegebenen Zugriffsrichtlinien durchläuft.</span><span class="sxs-lookup"><span data-stu-id="64f9b-119">Returns an enumerator that iterates through the collection of shared access policies.</span></span>
            </summary>
        <returns><span data-ttu-id="64f9b-120">Ein <see cref="T:System.Collections.Generic.IEnumerator`1" /> vom Typ <see cref="T:System.Collections.Generic.KeyValuePair`2" />.</span><span class="sxs-lookup"><span data-stu-id="64f9b-120">An <see cref="T:System.Collections.Generic.IEnumerator`1" /> of type <see cref="T:System.Collections.Generic.KeyValuePair`2" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.IsReadOnly" />
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
            <span data-ttu-id="64f9b-121">Ruft einen Wert, der angibt, ob die Auflistung der freigegebenen Zugriffsrichtlinien schreibgeschützt ist.</span><span class="sxs-lookup"><span data-stu-id="64f9b-121">Gets a value indicating whether the collection of shared access policies is read-only.</span></span> 
            </summary>
        <value>
          <span data-ttu-id="64f9b-122"><c>"true"</c> Wenn die Auflistung der freigegebenen Zugriffsrichtlinien schreibgeschützt ist, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="64f9b-122"><c>true</c> if the collection of shared access policies is read-only; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As SharedAccessQueuePolicy" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Item" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="64f9b-123">Eine Zeichenfolge, die mit dem Schlüssel des abzurufenden oder festzulegenden Werts.</span><span class="sxs-lookup"><span data-stu-id="64f9b-123">A string containing the key of the value to get or set.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-124">Ruft ab oder legt die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> mit dem angegebenen Schlüssel zugeordnete Element.</span><span class="sxs-lookup"><span data-stu-id="64f9b-124">Gets or sets the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> item associated with the specified key.</span></span>
            </summary>
        <value><span data-ttu-id="64f9b-125">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> mit dem angegebenen Schlüssel zugeordnete Element oder <c>null</c> Wenn Schlüssel nicht in die Auflistung der freigegebenen Zugriffsrichtlinien befindet.</span><span class="sxs-lookup"><span data-stu-id="64f9b-125">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> item associated with the specified key, or <c>null</c> if key is not in the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;string&gt; Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;string&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Keys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Keys As ICollection(Of String)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.ICollection&lt;string&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Keys" />
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
            <span data-ttu-id="64f9b-126">Ruft eine Auflistung mit den Schlüsseln in der Auflistung der freigegebenen Zugriffsrichtlinien ab.</span><span class="sxs-lookup"><span data-stu-id="64f9b-126">Gets a collection containing the keys in the shared access policies collection.</span></span>
            </summary>
        <value><span data-ttu-id="64f9b-127">Eine Auflistung von Zeichenfolgen, die mit den Schlüsseln der Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-127">A collection of strings containing the keys of the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Remove(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As KeyValuePair(Of String, SharedAccessQueuePolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; -&gt; bool&#xA;override this.Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; -&gt; bool" Usage="sharedAccessQueuePolicies.Remove item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="64f9b-128">Die <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, das mit einem Schlüssel und <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Wert aus der Auflistung der freigegebenen Zugriffsrichtlinien zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="64f9b-128">The <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object, containing a key and <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value, to remove from the shared access policies collection.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-129">Entfernt die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> in angegebener Wert der <see cref="T:System.Collections.Generic.KeyValuePair`2" /> Objekt, aus der Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-129">Removes the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> value, specified in the <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object, from the shared access policies collection.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="64f9b-130"><c>"true"</c> , wenn das Element erfolgreich entfernt; andernfalls wurde, <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="64f9b-130"><c>true</c> if the item was successfully removed; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Remove(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : string -&gt; bool&#xA;override this.Remove : string -&gt; bool" Usage="sharedAccessQueuePolicies.Remove key" />
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
        <param name="key"><span data-ttu-id="64f9b-131">Eine Zeichenfolge, die mit dem Schlüssel des der <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="64f9b-131">A string containing the key of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> item to remove.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-132">Entfernt den Wert mit dem angegebenen Schlüssel aus der Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-132">Removes the value with the specified key from the shared access policies collection.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="64f9b-133"><c>"true"</c> Wenn das Element erfolgreich gefunden und entfernt wurde, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="64f9b-133"><c>true</c> if the element is successfully found and removed; otherwise, <c>false</c>.</span></span> <span data-ttu-id="64f9b-134">Diese Methode gibt <c>"false"</c> , wenn der Schlüssel nicht gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="64f9b-134">This method returns <c>false</c> if the key is not found.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.System#Collections#IEnumerable#GetEnumerator" />
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
            <span data-ttu-id="64f9b-135">Gibt einen Enumerator, der die Auflistung der freigegebenen Zugriffsrichtlinien durchläuft.</span><span class="sxs-lookup"><span data-stu-id="64f9b-135">Returns an enumerator that iterates through the collection of shared access policies.</span></span>
            </summary>
        <returns><span data-ttu-id="64f9b-136">Ein <see cref="T:System.Collections.IEnumerator" /> -Objekt, das verwendet werden kann, zum Durchlaufen der Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-136">An <see cref="T:System.Collections.IEnumerator" /> object that can be used to iterate through the collection of shared access policies.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public bool TryGetValue (string key, out Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetValue(string key, [out] class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&amp; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.TryGetValue(System.String,Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValue (key As String, ByRef value As SharedAccessQueuePolicy) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetValue : string *  -&gt; bool&#xA;override this.TryGetValue : string *  -&gt; bool" Usage="sharedAccessQueuePolicies.TryGetValue (key, value)" />
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
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="64f9b-137">Eine Zeichenfolge mit dem Schlüssel des abzurufenden Werts.</span><span class="sxs-lookup"><span data-stu-id="64f9b-137">A string containing the key of the value to get.</span></span></param>
        <param name="value"><span data-ttu-id="64f9b-138">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> abzurufenden Elements.</span><span class="sxs-lookup"><span data-stu-id="64f9b-138">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> item to get.</span></span></param>
        <summary>
            <span data-ttu-id="64f9b-139">Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> mit dem angegebenen Schlüssel zugeordnete Element.</span><span class="sxs-lookup"><span data-stu-id="64f9b-139">Gets the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> item associated with the specified key.</span></span> 
            </summary>
        <returns><span data-ttu-id="64f9b-140">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Element mit dem angegebenen Schlüssel zugeordnet ist, wenn es sich bei der Schlüssel gefunden wurde; andernfalls der Standardwert für die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Typ.</span><span class="sxs-lookup"><span data-stu-id="64f9b-140">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> item associated with the specified key, if the key is found; otherwise, the default value for the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As ICollection(Of SharedAccessQueuePolicy)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicies.Values" />
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
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64f9b-141">Ruft eine Auflistung mit den Werten in der Auflistung der freigegebenen Zugriffsrichtlinien ab.</span><span class="sxs-lookup"><span data-stu-id="64f9b-141">Gets a collection containing the values in the shared access policies collection.</span></span>
            </summary>
        <value><span data-ttu-id="64f9b-142">Eine Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> Elemente in der Auflistung der freigegebenen Zugriffsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="64f9b-142">A collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> items in the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>